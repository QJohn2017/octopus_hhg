## Process this file with automake to produce Makefile.in

## Copyright (C) 2002 M. Marques, A. Castro, A. Rubio, G. Bertsch
##
## This program is free software; you can redistribute it and/or modify
## it under the terms of the GNU General Public License as published by
## the Free Software Foundation; either version 2, or (at your option)
## any later version.
##
## This program is distributed in the hope that it will be useful,
## but WITHOUT ANY WARRANTY; without even the implied warranty of
## MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
## GNU General Public License for more details.
##
## You should have received a copy of the GNU General Public License
## along with this program; if not, write to the Free Software
## Foundation, Inc., 59 Temple Place - Suite 330, Boston, MA
## 02111-1307, USA.
##
## $Id: Makefile.am 2771 2007-03-20 18:29:43Z lorenzen $

if COMPILE_METIS
  noinst_LIBRARIES = libmetis.a
endif

libmetis_a_SOURCES = \
	balance.c bucketsort.c ccgraph.c coarsen.c compress.c debug.c  \
	estmem.c fm.c fortran.c frename.c graph.c initpart.c kmetis.c  \
	kvmetis.c kwayfm.c kwayrefine.c kwayvolfm.c kwayvolrefine.c    \
	match.c mbalance.c mbalance2.c mcoarsen.c memory.c mesh.c      \
	meshpart.c mfm.c mfm2.c mincover.c minitpart.c minitpart2.c    \
	mkmetis.c mkwayfmh.c mkwayrefine.c mmatch.c mmd.c mpmetis.c    \
	mrefine.c mrefine2.c mutil.c myqsort.c ometis.c parmetis.c     \
	pmetis.c pqueue.c refine.c separator.c sfm.c srefine.c stat.c  \
	subdomains.c timing.c util.c

noinst_HEADERS = \
	defs.h macros.h metis.h proto.h rename.h struct.h

CLEANFILES = *~ *.bak
