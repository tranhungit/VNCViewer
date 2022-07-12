SID_LIST_LISTENER =
  (SID_LIST =
    (SID_DESC =
      (SID_NAME = CLRExtProc)
      (ORACLE_HOME = C:\app\oracle_user\product\12.1.0\dbhome_1)
      (PROGRAM = extproc)
      (ENVS = "EXTPROC_DLLS=ONLY:C:\app\oracle_user\product\12.1.0\dbhome_1\bin\oraclr12.dll")
    )
    (SID_DESC = 
        (GLOBAL_DBNAME = orcl)
        (ORACLE_HOME = C:\app\oracle_user\product\12.1.0\dbhome_1)
        (SID_NAME = orcl)
    )
  )
  
  LISTENER =
  (DESCRIPTION_LIST =
    (DESCRIPTION =
      (ADDRESS = (PROTOCOL = TCP)(HOST = localhost)(PORT = 1521))
      (ADDRESS = (PROTOCOL = IPC)(KEY = EXTPROC1521))
    )
  )
