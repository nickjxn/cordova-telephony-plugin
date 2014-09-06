<!---
    Licensed to the Apache Software Foundation (ASF) under one
    or more contributor license agreements.  See the NOTICE file
    distributed with this work for additional information
    regarding copyright ownership.  The ASF licenses this file
    to you under the Apache License, Version 2.0 (the
    "License"); you may not use this file except in compliance
    with the License.  You may obtain a copy of the License at

      http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing,
    software distributed under the License is distributed on an
    "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
    KIND, either express or implied.  See the License for the
    specific language governing permissions and limitations
    under the License.
-->
#me.nitroxis.cordova.telephony

Telephony
======

> The `NTX.telephony` object provide functions to make a call and SMS (without asking for the permission)


Methods
-------

- NTX.telephony.make_call()
- NTX.telephony.make_sms()


Installing
----------
> cordova plugin add 


Permissions
-----------

#### config.xml

            <uses-permission android:name="android.permission.SEND_SMS" />


iOS Quirks
----------
iOS don't allow making SMS without opening the message application but allows calling without asking user persmission.


Supported Platforms
-------------------

- iOS
- Android

