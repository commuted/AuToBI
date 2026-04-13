AuToBI: Automatic prosodic annotation.

Copyright (c) 2009-2017 Andrew Rosenberg

AuToBI is free software: you can redistribute it and/or modify
it under the terms of the Apache License included in this repository 
as LICENSE-2.0.txt

--changes by commuted
Updated to Java 8, fixed source abd tests 

Tests run: 859, Failures: 0, Errors: 0, Skipped: 1 Missing wav files

### Missing test audio files

The following unit test is currently failing because the required WAV files are not present in the `test_data/` directory:

| Missing file       | Test class                | Test method                                                                 |
|--------------------|---------------------------|-----------------------------------------------------------------------------|
| `test_villing.wav` | `VillingSyllabifierTest`  | `testVillingSyllabifierIDsSyllables`                                        |




Moved all dependancies to Maven

mvn package 

Makes an uber jar in project home: AuToBI.jar

To use the ant move dependancies to lib. 
