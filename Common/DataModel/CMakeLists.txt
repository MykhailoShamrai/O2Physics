# Copyright 2019-2020 CERN and copyright holders of ALICE O2.
# See https://alice-o2.web.cern.ch/copyright for details of the copyright holders.
# All rights not expressly granted are reserved.
#
# This software is distributed under the terms of the GNU General Public
# License v3 (GPL Version 3), copied verbatim in the file "COPYING".
#
# In applying this license CERN does not waive the privileges and immunities
# granted to it by virtue of its status as an Intergovernmental Organization
# or submit itself to any jurisdiction.

o2physics_add_header_only_library(DataModel
                                  HEADERS CaloClusters.h
                                          Centrality.h
                                          EventSelection.h
                                          FT0Corrected.h
                                          Multiplicity.h
                                          PIDResponse.h
                                          PIDResponseITS.h
                                          PIDResponseTOF.h
                                          PIDResponseTPC.h
                                          CollisionAssociationTables.h
                                          TrackSelectionTables.h
                                          McCollisionExtra.h
                                          Qvectors.h
                                          MatchMFTFT0.h
                                          MftmchMatchingML.h
                                          ZDCInterCalib.h
                                          EseTable.h
                                          FwdTrackReAlignTables.h)
