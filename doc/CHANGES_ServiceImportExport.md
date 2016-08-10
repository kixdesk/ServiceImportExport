# Change log of ServiceImportExport
* Copyright (C) 2006-2015 c.a.p.e. IT GmbH, http://www.cape-it.de/
* $Id$

# ROADMAP TASKS
* (201?/??/??) - CR: the big open to do: unit tests

# r5.0.0 (2015/11/17)
* (2015/11/17) - CR: 2015082690000535 (added changes for OTRS 5.0.x) (tlange)

# r4.0.0 (2015/05/13)
* (2015/05/13) - CR: version number normalization to common OTRS approach (tto)
* (2015/05/13) - CR: removed incomplete unit tests from package (tto)
* (2015/03/25) - Bugfix: (fixed bug create wrong preference handling) (fober)
* (2015/03/17) - CR: T2015031690000465 (create parent service, if it does not exists) (fober)
* (2015/03/17) - CR: T2015031690000465 (added custom ServicePreferences to Service import export mappings) (fober) 

# r1.4.0 (2014/12/02)
* (2014/12/02) - CR: T2014102990000492 (changes for framework 4.0.x) (alitvinova) 

# r1.3.2 (2014/10/29)
* (2014/06/13) - Bugfix: T2014052790000362 (fixed bug in SLA in use with GeneralCatalog but without ITSMCore) (tto) 

# r1.3.1 (2014/03/24)
* (2014/03/23) - Bugfix: T2014031890001088 (fixed import with ITSM 3.3.x) (alitvinova) 

# r1.3.0 (2013/10/17)
* (2013/10/17) - CR: (changes for use with OTRS 3.3.x) (millinger) 

# r1.2.1 (2012/08/26)
* (2013/08/23) - Bugfix: T2013081490000231 (service import showed wrong import summary) (smehlig) 

# r1.2.0 (2013/02/18)
* (2013/02/18) - CR: T2013021890000252 (added Sysconfig option for auotm. CSV-mapping creation on reinstall/upgrade) (alitvinova)
* (2013/02/18) - CR: T2013021890000252 (modifications for ITSM3.1.7 and framework OTRS 3.2.x) (alitvinova)

# r1.1.0 (2012/04/13)
* (2012/03/08) - CR: T2012022790000246 (modifications for OTRS 3.1.x) (alitvinova)
* (2012/03/08) - CR: T2012022790000246 (deleted "Export with labels" attribute) (alitvinova)

# r1.0.3 (2011/11/29)
* (2011/11/29) - CR: set required ImportExport to version 3.0.1 (tto)
* (2011/11/29) - CR: removed html-version of pod documentation (tto)
* (2011/11/29) - CR: added custom SLAPreferences to SLA import export mappings (tto)
* (2011/11/29) - CR: removed "export with labels" (now included in ImportExport-framework (tto)

# r1.0.2 (2011/04/07)
* (2011/07/04) - Bugfix: removed uncommentation of some code (tto)

# r1.0.1 (2011/04/07)
* (2011/07/04) - CR: added custom ServicePreferences to service import export mappings (tto)
* (2011/03/20) - CR: moved usage information to pod-file in <OTRS_HOME>/doc/en
* (2011/03/19) - Bugfix: fixed bug installation if GeneralCatalog is installed but not ITSMCore

# r1.0.0 (2011/03/08)
* (2011/03/08) - CR: file USAGE_serviceimportexport for documentation purpose.

# r0.6.0 (2011/01/21)
* (2011/02/09) - CR: added some error handlings in package setup method
* (2011/01/21) - CR: changes for use with OTRS 3.0.x

# r0.5.8 (2010/07/30)
* (2010/07/30) - Bugfix: fixed use of uninitialized value in comparison

# r0.5.7 (2010/07/30)
* (2010/07/30) - Bugfix: fixed use of wrong hash key in Service-Backend

# r0.5.6 (2010/07/30)
* (2010/07/30) - Bugfix: column separator not set correctly

# r0.5.5 (2010/04/27)
* (2010/04/27) - Bugfix: auto-created mapping for AssignedService.

# r0.5.4 (2010/04/22)
* (2010/04/22) - Bugfix: missing variable declaration.

# r0.5.3 (2010/04/21)
* (2010/04/21) - Bugfix: missing variable declaration.

# r0.5.2 (2010/04/21)
* (2010/04/21) - Bugfix: removed "my" from package installation.

# r0.5.1 (2010/04/21)
* (2010/04/20) - CR: finalized mapping creation during installation

# r0.5.0 (2010/04/17)
* (2010/04/17) - CR: First pre-productive release of general service import-/export backend.
* (2010/04/16) - CR: automatic ex-/import-mapping creation on package installation
* (2010/04/15) - CR: added unit-test files (preparations only)
* (2010/04/15) - CR: added ex-/import backend fur SLA definition
* (2010/04/13) - CR: added ex-/import backend fur Service
* (2010/04/12) - CR: added ex-/import backend fur Service2CustomerUser
* (2010/04/09) - CR: initial package setup
