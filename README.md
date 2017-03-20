# A starter android app with Retrofit + RxJava + RetroLambda + Glide + Butterknife

**MyNewApp** is a starter android app with most commonly used config and third party libraries.

## Libraries Included:

- RxJava and RxAndroid
- [retrolambda expressions](http://guides.codepath.com/android/Lambda-Expressions)
- [Glide](http://inthecheesefactory.com/blog/get-to-know-glide-recommended-by-google/en) for more efficient image rendering.
- [Retrofit networking library](http://guides.codepath.com/android/Consuming-APIs-with-Retrofit)
- [GSON library](http://guides.codepath.com/android/Using-Android-Async-Http-Client#decoding-with-gson-library) to streamline the parsing of JSON data.


### Other Configuration

- To include Vercor Drawables, the app/build.gradle includes:
    ```
    defaultConfig {
        vectorDrawables.useSupportLibrary = true
    }
    ```

- You can use DataBindingUtils out of box with this option included in app/build.gradle
    ```
    defaultConfig {
        dataBinding.enabled = true
    }

    ```

## License

    Copyright 2017 Radhika Karandikar

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
