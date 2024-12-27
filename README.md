# Unhandled FormatException in Dart JSON Decoding

This example showcases a common error in Dart applications involving network requests and JSON parsing.  The `fetchData` function fetches data from an API, but doesn't handle the `FormatException` that can occur if `jsonDecode` receives invalid JSON.  The solution demonstrates robust error handling.