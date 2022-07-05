# Crypt
*Encryption Decryption for Android Apps*

**Add it to your root build.gradle**
```
    allprojects {
        repositories {
            ...
            maven {
                url 'https://jitpack.io'
            }
        }
    }
```

**Add the dependency to app build.gradle**
```
    dependencies {
        implementation 'com.github.nevidelia:Crypt:1.0.0'
    }
```

**How it works?**
```
    Crypt crypt = new Crypt();
```

**Encryption**
```
    // encrypt a decrypted string

    // pass key and decrypted string
    String encrypted = crypt.encrypt(KEY, MESSAGE));
    textView.setText(encrypted);
```

**Decryption**
```
    // decrypt an encryped string

    // pass key and encryped string
    String decrypted = crypt.decrypt(KEY, ENCRYPTED));
    textView.setText(decrypted);
```

**License**
```
    Copyright 2022 Nevidelia Inc.

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
```
