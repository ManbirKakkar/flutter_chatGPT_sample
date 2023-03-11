# ChatGPT API with Flutter
This code is a Flutter implementation of the ChatGPT API, which allows developers to easily
integrate AI-powered chatbots into their applications.

# Installation
Clone the repository or download the code as a ZIP file.
Open the project in your preferred IDE or editor.
Run flutter pub get to install the required dependencies.

# Usage

To use the ChatGPT API with Flutter, you need to obtain an API key from the ChatGPT website. Once
you have your API key, you can create an instance of the ChatGPTApi class and call the getResponse()
method with a prompt to get a response from the API.

```
final chatGPTApi = ChatGPTApi('YOUR_API_KEY');
final response = await chatGPTApi.getResponse('Hello, how are you?');
print(response);
```

# Dependencies
This code requires the http package, which can be installed by running flutter pub get.

# License
This code is licensed under the MIT License. See the LICENSE file for details.

# Support
If you have any questions or issues with this code, please feel free to contact me at kakkar.manbir11@gmail.com.

# Resources
[ChatGPT API documentation] (https://platform.openai.com/docs/api-reference/introduction)
[Flutter documentation] (https://docs.flutter.dev/)
[http package documentation] (https://pub.dev/packages/http)

# Contributions
Contributions are welcome! If you would like to contribute to this code, please submit a pull request.
