## React Native ActivityIndicator Crash on Android

This repository demonstrates a bug where a React Native app crashes on Android when using the ActivityIndicator component. The crash occurs under specific circumstances, such as when fetching data and rendering the ActivityIndicator within a FlatList.  The error message provided by Android is often unhelpful, making debugging difficult.

The bug is primarily reproduced on Android.  iOS runs the application without crashing.

This repository includes both the buggy code and a solution that resolves the Android crash while maintaining functionality.