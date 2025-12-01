The manually written sorting function uses Python’s built-in sorted() and a lambda expression, making it simple, readable, and efficient for most use cases. It assumes all dictionaries contain the key, so its performance is predictable and minimal.

The AI-generated version from GitHub Copilot includes additional features such as error handling and the use of .get(), which prevents runtime errors when a dictionary is missing a key. This makes it slightly more robust in uncontrolled environments. However, this robustness adds unnecessary complexity for a small function and may slow performance due to exception handling overhead.

In terms of efficiency, the manual version is faster and more direct. The AI-generated version is “safer” but slightly slower and harder to read. This demonstrates that AI tools can assist with defensive programming but still require human judgment to decide whether the added complexity is needed.

Overall, AI speeds up development and generates working code quickly, but manual review remains essential.
