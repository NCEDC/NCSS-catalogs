# NCSS-catalogs
These files contain the earthquake parameters catalog of the Northern California Seismic Network from 1966 to present.
They are available in the EHP CSV format. For documentation on the format, please go to:

https://earthquake.usgs.gov/earthquakes/feed/v1.0/csv.php

A current snapshot of these files can be found at:

http://ncedc.org/ftp/pub/catalogs/NCSS-catalogs/

The index.txt file contains a mapping between the commit times and the hash keys and can be used to retrieve a version of the catalog at a given time.

NCEDC Specific field values:

  status: (Event status)
  
          A: Automatic
          F: Finalized
          H: Human Reviewed
          I: Intermediate
          
  magType: (Magnitude Type)
  
          a : Primary amplitude magnitude (Jerry Eaton's XMAG)
          b : Body-wave magnitude
          d : Duration magnitude
          dl: Low-gain initial P-wave amplitude magnitude
          e : Energy magnitude
          h : Human assigned magnitude
          l : Local magnitude
          n : No magnitude
          un: Unknown magnitude type
          w : Moment magnitude
          
  type: (EventType)
  
          bc: Building collapse/demolition
          eq: Earthquake
          ex: Generic chemical blast
          lp: Long period volcanic earthquake
          ls: Landslide
          mi: Meteor/comet impact
          nt: Nuclear test
          ot: Other miscellaneous
          qb: Quarry blast
          rs: Rockslide
          sh: Refraction/reflection survey shot
          sn: Sonic shockwave
          st: Subnet trigger
          th: Thunder
          uk: Unknown type
