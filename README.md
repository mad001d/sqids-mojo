# Sqids Mojo: Generate Short Unique IDs with Ease 🚀

![GitHub Repo Stars](https://img.shields.io/github/stars/mad001d/sqids-mojo?style=social) ![GitHub Release](https://img.shields.io/github/release/mad001d/sqids-mojo.svg) ![GitHub Issues](https://img.shields.io/github/issues/mad001d/sqids-mojo) ![GitHub Forks](https://img.shields.io/github/forks/mad001d/sqids-mojo?style=social)

Welcome to the official Mojo port of Sqids! This project allows you to generate short unique IDs from numbers. With a focus on simplicity and efficiency, Sqids Mojo provides a straightforward way to create unique identifiers for your applications.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Examples](#examples)
- [Contributing](#contributing)
- [License](#license)
- [Support](#support)

## Features

- **Fast Generation**: Quickly generate unique IDs from numeric inputs.
- **Simple API**: Easy-to-use interface for seamless integration.
- **Mojo Language**: Leverage the power of Mojo for efficient execution.
- **Short URLs**: Create short URLs for better user experience.
- **Unique Identifiers**: Ensure uniqueness for IDs across your applications.

## Installation

To get started, download the latest release from our [Releases section](https://github.com/mad001d/sqids-mojo/releases). After downloading, follow the instructions to execute the program.

1. **Download the latest release**: Visit [Releases](https://github.com/mad001d/sqids-mojo/releases) and download the appropriate file for your system.
2. **Execute the file**: Run the downloaded file to start generating short unique IDs.

## Usage

Using Sqids Mojo is straightforward. After installation, you can start generating IDs by following these simple steps:

1. **Import the Library**: Import the Sqids library in your Mojo application.
2. **Generate IDs**: Call the appropriate functions to generate short unique IDs.

### Example Code

```mojo
import Sqids

// Create a new Sqids instance
let sqids = Sqids()

// Generate a unique ID from a number
let uniqueID = sqids.generate(12345)
print(uniqueID) // Outputs a short unique ID
```

## Examples

Here are some examples of how to use Sqids Mojo in different scenarios:

### Generating Short Unique IDs

```mojo
import Sqids

let sqids = Sqids()

for number in 1...10 {
    let id = sqids.generate(number)
    print("Number: \(number) => Short ID: \(id)")
}
```

### Creating Short URLs

You can also use Sqids Mojo to create short URLs:

```mojo
import Sqids

let sqids = Sqids()
let originalURL = "https://example.com/very-long-url"
let shortID = sqids.generate(123456)
let shortURL = "https://short.url/\(shortID)"

print("Original URL: \(originalURL)")
print("Short URL: \(shortURL)")
```

## Contributing

We welcome contributions to Sqids Mojo! If you have suggestions, improvements, or bug fixes, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or fix.
3. Make your changes and commit them.
4. Push to your branch.
5. Create a pull request.

Your contributions help make this project better for everyone!

## License

Sqids Mojo is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Support

If you have any questions or need assistance, feel free to reach out through the [Issues section](https://github.com/mad001d/sqids-mojo/issues) of this repository. 

For more information, visit our [Releases section](https://github.com/mad001d/sqids-mojo/releases) to download the latest version and stay updated.

Thank you for checking out Sqids Mojo! We hope you find it useful in your projects. Happy coding!