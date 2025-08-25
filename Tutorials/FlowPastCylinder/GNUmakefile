#AMREX_HOME defines the directory in which we will find the AMReX directory
AMREX_HOME       ?= /usr/local/amrex
AMREX_HYDRO_HOME ?= /usr/local/AMReX-Hydro

#TOP defines the directory in which we will find Source, Exec, etc.
TOP = ../..

#
# Variables for the user to set ...
#

PRECISION   = DOUBLE

# running 2d inputs files requires a 2d executable set here
DIM         = 3
COMP        = gnu

DEBUG       = FALSE
USE_MPI     = TRUE
USE_OMP     = FALSE
PROFILE     = FALSE


USE_VELOCITY = FALSE

USE_EB = TRUE

EBASE = amr

Blocs   := .

include $(TOP)/Exec/Make.IAMR
