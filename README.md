# android-network-demo
Source code that demonstrates the network operations in Android. Including:
* Basic HTTP operation with HttpUrlConnection
* Run network operations in a worker / background thread using AsyncTask
* Implementing headless / model fragment which encapsulates the network operations in AsyncTask
* Implementation of a Volley singleton that encapsulates RequestQueue and other Volley functionality to perform various requests (e.g. the built-in JsonObjectRequest and the custom GsonRequest written by the author of Volley, Ficus Kirkpatrick)
* Demostrate of different LruCache implementations (number or sizes of entries) for Volley's ImageLoader

# License
This demo is developed to be used in Android Development training conducted by CodePlay Studio. It is lisenced under the Apache License, Version 2.0 (the "License"); You may not use this demo except in compliance with the License. You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

The source code is provided "AS IS". Any expressed or implied warranties, including, but not limited to, the implied warranties of merchantability and fitness for a particular purpose are disclaimed. In no event shall the copyright holder be liable for any direct, indirect, incidental, special, exemplary, or consequential damages (Including, but not limited to, procurement of goods or services; loss of use, data, or profits; or business interruption) however caused and on any theory of liability, whether in contract, strict liability, or tort (Including negligence or otherwise) arising in any way out of the use of this source code, even if advised of the possibility of such damage.

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the above copyright notice and disclaimer are retained in the redistributions of source code or reproduced in the documentation and/or other materials provided with the redistributions in binary form.
