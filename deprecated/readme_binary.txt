 ****************************************************************************
 * Copyright (C) 2007-2008 OpenIntents.org                                  *
 *                                                                          *
 * Licensed under the Apache License, Version 2.0 (the "License");          *
 * you may not use this file except in compliance with the License.         *
 * You may obtain a copy of the License at                                  *
 *                                                                          *
 *      http://www.apache.org/licenses/LICENSE-2.0                          *
 *                                                                          *
 * Unless required by applicable law or agreed to in writing, software      *
 * distributed under the License is distributed on an "AS IS" BASIS,        *
 * WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. *
 * See the License for the specific language governing permissions and      *
 * limitations under the License.                                           *
 ****************************************************************************

OpenIntents defines and implements open interfaces for
improved interoperability of Android applications.

To obtain the current release, visit
  http://www.openintents.org

-----------------------------------------------------------------------------

OpenIntents

The directory structure is organized as follows:

openintents.apk    the main program

lib/               contains the latest library JAR version

samples/           contains samples that use OpenIntents

tools/             contains additional tools like the SensorSimulator

-----------------------------------------------------------------------------

To install an application from the command line:

* run the emulator:
  emulator

* install the main program and optionally any of the sample programs:
  adb install OpenIntents.apk
  adb install samples/PresentPicker.apk

* run the program from the Applications folder within the emulator.
