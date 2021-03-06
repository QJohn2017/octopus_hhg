# @HEADER
##############################################################################
# Zoltan Library for Parallel Applications                                   #
# Copyright (c) 2000,2001,2002, Sandia National Laboratories.                #
# This software is distributed under the GNU Lesser General Public License.  #
# For more info, see the README file in the top-level Zoltan directory.      #
##############################################################################
# @HEADER

# The following line helps the test harness recover from build errors.

ALL_H = \
	$(srcdir)/all/all_allo_const.h

ALL = \
	$(srcdir)/all/all_allo.c

COLORING_H = \
	$(srcdir)/coloring/coloring_const.h \
	$(srcdir)/coloring/coloring.h \
	$(srcdir)/coloring/g2l_hash.h

COLORING = \
	$(srcdir)/coloring/coloring.c \
	$(srcdir)/coloring/color_test.c \
	$(srcdir)/coloring/g2l_hash.c

HA_H = \
	$(srcdir)/ha/ha_const.h \
	$(srcdir)/ha/ha_drum.h

HA = \
	$(srcdir)/ha/build_machine_desc.c \
	$(srcdir)/ha/divide_machine.c \
	$(srcdir)/ha/get_processor_name.c \
	$(srcdir)/ha/ha_drum.c

HIER_H = \
	$(srcdir)/hier/hier.h

HIER = \
	$(srcdir)/hier/hier.c \
	$(srcdir)/hier/hier_free_struct.c

HSFC_H = \
	$(srcdir)/hsfc/hsfc.h \
	$(srcdir)/hsfc/hsfc_const.h \
	$(srcdir)/hsfc/hsfc_hilbert_const.h

HSFC = \
	$(srcdir)/hsfc/hsfc_box_assign.c \
	$(srcdir)/hsfc/hsfc.c \
	$(srcdir)/hsfc/hsfc_hilbert.c \
	$(srcdir)/hsfc/hsfc_point_assign.c

INCLUDE_H = \
	$(srcdir)/include/lbi_const.h \
	$(srcdir)/include/zoltan_align.h \
	$(srcdir)/include/zoltan_cpp.h \
	$(srcdir)/include/zoltan.h \
	$(srcdir)/include/zoltan_types.h \
	$(srcdir)/include/zoltan_comm.h \
	$(srcdir)/include/zoltan_comm_cpp.h \
	$(srcdir)/include/zoltan_timer_cpp.h \
	$(srcdir)/include/zoltan_timer.h \
	$(srcdir)/include/zoltan_dd.h \
	$(srcdir)/include/zoltan_dd_cpp.h \
	$(srcdir)/include/zoltan_mem.h  

LB_H = \
	$(srcdir)/lb/lb_const.h \
	$(srcdir)/lb/lb_init_const.h

LB = \
	$(srcdir)/lb/lb_balance.c \
	$(srcdir)/lb/lb_box_assign.c \
	$(srcdir)/lb/lb_copy.c \
	$(srcdir)/lb/lb_eval.c \
	$(srcdir)/lb/lb_free.c \
	$(srcdir)/lb/lb_init.c \
	$(srcdir)/lb/lb_invert.c \
	$(srcdir)/lb/lb_migrate.c \
	$(srcdir)/lb/lb_part2proc.c \
	$(srcdir)/lb/lb_point_assign.c \
	$(srcdir)/lb/lb_remap.c \
	$(srcdir)/lb/lb_set_fn.c \
	$(srcdir)/lb/lb_set_method.c \
	$(srcdir)/lb/lb_set_part_sizes.c

EXTRA_OCT_H = \
	$(srcdir)/oct/costs_const.h \
	$(srcdir)/oct/costs.h \
	$(srcdir)/oct/dfs_const.h \
	$(srcdir)/oct/dfs.h \
	$(srcdir)/oct/migoct_const.h \
	$(srcdir)/oct/migreg_const.h \
	$(srcdir)/oct/migreg.h \
	$(srcdir)/oct/migtags_const.h \
	$(srcdir)/oct/msg_const.h \
	$(srcdir)/oct/octant_const.h \
	$(srcdir)/oct/octree_const.h \
	$(srcdir)/oct/octupdate_const.h \
	$(srcdir)/oct/octupdate.h \
	$(srcdir)/oct/oct_util_const.h \
	$(srcdir)/oct/rootlist_const.h \
	$(srcdir)/oct/SFC.h

EXTRA_OCT = \
	$(srcdir)/oct/costs.c \
	$(srcdir)/oct/dfs.c \
	$(srcdir)/oct/migoct.c \
	$(srcdir)/oct/migreg.c \
	$(srcdir)/oct/migtags.c \
	$(srcdir)/oct/msg.c \
	$(srcdir)/oct/octant.c \
	$(srcdir)/oct/oct_plot.c \
	$(srcdir)/oct/octree.c \
	$(srcdir)/oct/octupdate.c \
	$(srcdir)/oct/oct_util.c \
	$(srcdir)/oct/output.c \
	$(srcdir)/oct/rootlist.c

OCT_H = $(EXTRA_OCT_H)

OCT = $(EXTRA_OCT)

ORDER_H = \
	$(srcdir)/order/order_const.h

ORDER = \
	$(srcdir)/order/order.c \
	$(srcdir)/order/order_struct.c \
	$(srcdir)/order/order_tools.c \
	$(srcdir)/order/perm.c

PAR_H = \
	$(srcdir)/par/par_average_const.h \
	$(srcdir)/par/par_bisect_const.h \
	$(srcdir)/par/par_const.h \
	$(srcdir)/par/par_median_const.h \
	$(srcdir)/par/par_tflops_special_const.h

PAR = \
	$(srcdir)/par/par_average.c \
	$(srcdir)/par/par_bisect.c \
	$(srcdir)/par/par_median.c \
	$(srcdir)/par/par_median_randomized.c \
	$(srcdir)/par/par_stats.c \
	$(srcdir)/par/par_sync.c \
	$(srcdir)/par/par_tflops_special.c

PARAMS_H = \
	$(srcdir)/params/key_params.h \
	$(srcdir)/params/params_const.h

PARAMS = \
	$(srcdir)/params/assign_param_vals.c \
	$(srcdir)/params/bind_param.c \
	$(srcdir)/params/check_param.c \
	$(srcdir)/params/free_params.c \
	$(srcdir)/params/key_params.c \
	$(srcdir)/params/print_params.c \
	$(srcdir)/params/set_param.c

PARMETIS_H = \
	$(srcdir)/parmetis/third_library.h \
	$(srcdir)/parmetis/third_library_tools.h \
	$(srcdir)/parmetis/third_library_const.h

PARMETIS = \
        $(srcdir)/parmetis/build_graph.c \
        $(srcdir)/parmetis/postprocessing.c \
        $(srcdir)/parmetis/preprocessing.c \
        $(srcdir)/parmetis/scatter_graph.c \
        $(srcdir)/parmetis/third_library.c \
        $(srcdir)/parmetis/verify_graph.c


PHG_H = \
	$(srcdir)/phg/phg_comm.h \
	$(srcdir)/phg/phg_const.h \
	$(srcdir)/phg/phg_distrib.h \
	$(srcdir)/phg/phg.h \
	$(srcdir)/phg/phg_hypergraph.h \
	$(srcdir)/phg/phg_util.h

PHG = \
	$(srcdir)/phg/phg_build.c \
	$(srcdir)/phg/phg_build_calls.c \
	$(srcdir)/phg/phg.c \
	$(srcdir)/phg/phg_coarse.c \
	$(srcdir)/phg/phg_comm.c \
	$(srcdir)/phg/phg_distrib.c \
	$(srcdir)/phg/phg_gather.c \
	$(srcdir)/phg/phg_hypergraph.c \
	$(srcdir)/phg/phg_match.c \
	$(srcdir)/phg/phg_order.c \
	$(srcdir)/phg/phg_parkway.c \
	$(srcdir)/phg/phg_patoh.c \
	$(srcdir)/phg/phg_plot.c \
	$(srcdir)/phg/phg_rdivide.c \
	$(srcdir)/phg/phg_refinement.c \
	$(srcdir)/phg/phg_scale.c \
	$(srcdir)/phg/phg_serialpartition.c \
	$(srcdir)/phg/phg_util.c \
	$(srcdir)/phg/phg_Vcycle.c

RCB_H = \
	$(srcdir)/rcb/create_proc_list_const.h \
	$(srcdir)/rcb/rcb_const.h \
	$(srcdir)/rcb/rcb.h \
	$(srcdir)/rcb/rib_const.h \
	$(srcdir)/rcb/rib.h \
	$(srcdir)/rcb/shared.h

RCB = \
	$(srcdir)/rcb/box_assign.c \
	$(srcdir)/rcb/create_proc_list.c \
	$(srcdir)/rcb/inertial1d.c \
	$(srcdir)/rcb/inertial2d.c \
	$(srcdir)/rcb/inertial3d.c \
	$(srcdir)/rcb/point_assign.c \
	$(srcdir)/rcb/rcb_box.c \
	$(srcdir)/rcb/rcb.c \
	$(srcdir)/rcb/rcb_util.c \
	$(srcdir)/rcb/rib.c \
	$(srcdir)/rcb/rib_util.c \
	$(srcdir)/rcb/shared.c

REFTREE_H = \
	$(srcdir)/reftree/reftree_const.h \
	$(srcdir)/reftree/reftree.h

REFTREE = \
	$(srcdir)/reftree/reftree_build.c \
	$(srcdir)/reftree/reftree_coarse_path.c \
	$(srcdir)/reftree/reftree_hash.c \
	$(srcdir)/reftree/reftree_part.c

SIMPLE = \
	$(srcdir)/simple/block.c \
	$(srcdir)/simple/random.c

TIMER_H = \
	$(srcdir)/timer/timer_const.h

TIMER = \
	$(srcdir)/timer/timer_params.c

UTILITIES_H = \
	$(srcdir)/Utilities/Communication/comm.h \
	$(srcdir)/Utilities/DDirectory/DD.h \
	$(srcdir)/Utilities/Timer/timer.h \
	$(srcdir)/Utilities/shared/zoltan_util.h \
	$(srcdir)/Utilities/shared/zoltan_id.h

UTILITIES = \
	$(srcdir)/Utilities/Communication/comm_exchange_sizes.c \
	$(srcdir)/Utilities/Communication/comm_invert_map.c \
	$(srcdir)/Utilities/Communication/comm_do.c \
	$(srcdir)/Utilities/Communication/comm_do_reverse.c \
	$(srcdir)/Utilities/Communication/comm_info.c \
	$(srcdir)/Utilities/Communication/comm_create.c \
	$(srcdir)/Utilities/Communication/comm_resize.c \
	$(srcdir)/Utilities/Communication/comm_sort_ints.c \
	$(srcdir)/Utilities/Communication/comm_destroy.c \
	$(srcdir)/Utilities/Communication/comm_invert_plan.c \
	$(srcdir)/Utilities/Timer/zoltan_timer.c \
	$(srcdir)/Utilities/Timer/timer.c \
	$(srcdir)/Utilities/DDirectory/DD_Find.c \
	$(srcdir)/Utilities/DDirectory/DD_Destroy.c \
	$(srcdir)/Utilities/DDirectory/DD_Set_Neighbor_Hash_Fn3.c \
	$(srcdir)/Utilities/DDirectory/DD_Remove.c \
	$(srcdir)/Utilities/DDirectory/DD_Create.c \
	$(srcdir)/Utilities/DDirectory/DD_Update.c \
	$(srcdir)/Utilities/DDirectory/DD_Stats.c \
	$(srcdir)/Utilities/DDirectory/DD_Hash2.c \
	$(srcdir)/Utilities/DDirectory/DD_Print.c \
	$(srcdir)/Utilities/DDirectory/DD_Set_Neighbor_Hash_Fn2.c \
	$(srcdir)/Utilities/DDirectory/DD_Set_Hash_Fn.c \
	$(srcdir)/Utilities/DDirectory/DD_Set_Neighbor_Hash_Fn1.c \
	$(srcdir)/Utilities/Memory/mem.c \
	$(srcdir)/Utilities/shared/zoltan_align.c \
	$(srcdir)/Utilities/shared/zoltan_id.c

ZZ_H = \
	$(srcdir)/zz/zz_const.h \
	$(srcdir)/zz/zz_heap.h \
	$(srcdir)/zz/zz_id_const.h \
	$(srcdir)/zz/zz_rand.h \
	$(srcdir)/zz/zz_sort.h \
	$(srcdir)/zz/zz_util_const.h

ZZ = \
	$(srcdir)/zz/zz_coord.c \
	$(srcdir)/zz/zz_gen_files.c \
	$(srcdir)/zz/zz_hash.c \
	$(srcdir)/zz/zz_heap.c \
	$(srcdir)/zz/zz_init.c \
	$(srcdir)/zz/zz_obj_list.c \
	$(srcdir)/zz/zz_rand.c \
	$(srcdir)/zz/zz_set_fn.c \
	$(srcdir)/zz/zz_sort.c \
	$(srcdir)/zz/zz_struct.c \
	$(srcdir)/zz/zz_util.c

# ------------------------------------------------------------------------
# Zoltan library specifications
# ------------------------------------------------------------------------
ZOLTAN_LIB = libzoltan.a

ZOLTAN_H = \
	$(ALL_H) \
	$(COLORING_H) \
	$(HA_H) \
	$(HIER_H) \
	$(HSFC_H) \
	$(INCLUDE_H) \
	$(LB_H) \
	$(OCT_H) \
	$(ORDER_H) \
	$(PAR_H) \
	$(PARAMS_H) \
	$(PARMETIS_H) \
	$(PHG_H) \
	$(RCB_H) \
	$(REFTREE_H) \
	$(TIMER_H) \
	$(UTILITIES_H) \
	$(ZZ_H)

libzoltan_a_SOURCES = \
	$(ALL) \
	$(COLORING) \
	$(HA) \
	$(HIER) \
	$(HSFC) \
	$(LB) \
	$(OCT) \
	$(ORDER) \
	$(PAR) \
	$(PARAMS) \
	$(PARMETIS) \
	$(PHG) \
	$(RCB) \
	$(REFTREE) \
	$(SIMPLE) \
	$(TIMER) \
	$(UTILITIES) \
	$(ZZ)

EXTRA_libzoltan_a_SOURCES = \
	$(EXTRA_OCT_H) \
	$(EXTRA_OCT)

EXPORT_INCLUDES = \
	-I$(srcdir)/Utilities/shared \
	-I$(srcdir)/Utilities/Timer  \
	-I$(srcdir)/zz               \
	-I$(srcdir)/all              \
	-I$(srcdir)/par              \
	-I$(srcdir)/order            \
	-I$(srcdir)/params           \
	-I$(srcdir)/phg              \
	-I$(srcdir)/rcb              \
	-I$(srcdir)/timer            \
	-I$(srcdir)/hsfc             \
	-I$(srcdir)/coloring         \
	-I$(srcdir)/hier             \
	-I$(srcdir)/reftree          \
	-I$(srcdir)/parmetis         \
	-I$(srcdir)/ha               \
	-I$(srcdir)/include          \
	-I$(srcdir)/fort             \
	-I$(srcdir)/lb


AM_CPPFLAGS = $(EXPORT_INCLUDES)

# ------------------------------------------------------------------------
# List of all libraries to install in $(libexecdir)
# ------------------------------------------------------------------------

if COMPILE_ZOLTAN
  noinst_LIBRARIES = $(ZOLTAN_LIB)
endif

# ------------------------------------------------------------------------
# List of all headers to install in $(includedir)
# ------------------------------------------------------------------------

# Eventually we will try to install fewer headers
noinst_HEADERS = $(INCLUDE_H) 

ZOLTAN_POSTPROCESS = \
    $(srcdir)/postprocessing/bin/toscotchperm.py \
    $(srcdir)/postprocessing/ordering/README \
    $(srcdir)/postprocessing/ordering/mm_input.c \
    $(srcdir)/postprocessing/ordering/mm_input.h \
    $(srcdir)/postprocessing/ordering/order_eval.c \
    $(srcdir)/postprocessing/ordering/order_eval.h \
    $(srcdir)/postprocessing/ordering/ordering.py \
    $(srcdir)/postprocessing/ordering/toscotchperm.py \
    $(srcdir)/postprocessing/ordering/zdrive.inp \
    $(srcdir)/postprocessing/ordering/zdrive.inp.parmetis \
    $(srcdir)/postprocessing/ordering/zdrive.inp.scotch

EXTRA_DIST = $(ZOLTAN_H) \
    $(srcdir)/Utilities/Communication/README \
    $(srcdir)/Utilities/Memory/README \
    $(srcdir)/Utilities/Timer/README \
    $(srcdir)/Utilities/DDirectory/README \
    $(srcdir)/Utilities/README \
    $(NATIVE_ZOLTAN_BUILD) \
    $(ZOLTAN_POSTPROCESS)
