# DataExplorer

The National Hurricane Center (NHC) keeps records of tropical cyclones (tropical depressions, tropical storms, hurricanes, post-tropical depressions, etc.) in the Atlantic Basin and in the North Pacific Ocean. This analysis uses both the Atlantic Ocean database and the Pacific Ocean database to explore possible relationships/differences between tropical cyclones classified as hurricanes (wind speeds greater than 64 kts) in the Atlantic and Pacific Oceans. This analysis also yields several new databases, including databases filtered by maximum recorded wind speeds and minimum recorded central pressure, as well as data sets encompassing both Atlantic and Pacific Ocean tropical cyclone data.

The NHC publishes the tropical cyclone data in HURDAT2 (Huricane Database 2) format. The databases contain six-hourly measurements at 00z, 06z, 12z, and 18z. Each record consists of the following:
    ID - two letter code (AL - Atlantic, EP - Pacific) followed by six numbers
    Name - the name of the tropical cyclone (NOTE: tropical depressions are not named, and hurricanes were not named prior to 1953)
    Date - YYYYMMDD
    Time - H or HMM or HHMM (all times UTC)
    Event - Identifies the record. Options are:
        C - closest approach to a coast (did not make landfall)
        G - genesis
        I - intensity peak (both pressure and wind)
        L - landfall
        P - minimum central pressure
        R - rapid intensity changes
        S - change of status (see Status below)
        T - track (position) of cyclone
        W - maximum sustained wind speed
    Status - Status of the system. Options are:
        TD - tropical depression
        TS - tropical storm
        HU - hurricane
        EX - extratropical cyclone
        SD - subtropical depression
        SS - subtropical storm
        LO - low pressure system (not tropical, subtropical, nor extratropical)
        WV - tropical wave
        DB - disturbance
    Latitude - latitude of center of cyclone
    Longitude - longitude of center of cyclone
    Maximum Wind - maximum sustained wind (kts)
    Minimum Pressure - minimum central pressure (mb)
    Low Wind NE - 34 kt wind radii maximum extent in northeastern quadrant (nm)
    Low Wind SE - 34 kt wind radii maximum extent in southeastern quadrant (nm)
    Low Wind SW - 34 kt wind radii maximum extent in southwestern quadrant (nm)
    Low Wind NW - 34 kt wind radii maximum extent in northwestern quadrant (nm)
    Moderate Wind NE - 50 kt wind radii maximum extent in northeastern quadrant (nm)
    Moderate Wind SE - 50 kt wind radii maximum extent in southeastern quadrant (nm)
    Moderate Wind SW - 50 kt wind radii maximum extent in southwestern quadrant (nm)
    Moderate Wind NW - 50 kt wind radii maximum extent in northwestern quadrant (nm)
    High Wind NE - 64 kt wind radii maximum extent in northeastern quadrant (nm)
    High Wind SE - 64 kt wind radii maximum extent in southeastern quadrant (nm)
    High Wind SW - 64 kt wind radii maximum extent in southwestern quadrant (nm)
    High Wind NW - 64 kt wind radii maximum extent in northwestern quadrant (nm)
