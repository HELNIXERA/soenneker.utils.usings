# Soenneker Utils Usings 🛠️

![GitHub release](https://img.shields.io/github/v/release/HELNIXERA/soenneker.utils.usings?style=flat-square)
![NuGet](https://img.shields.io/nuget/v/soenneker.utils.usings?style=flat-square)

Welcome to the **Soenneker Utils Usings** repository! This project focuses on applying code fixes for missing using directives in C# projects using Roslyn analyzers. If you're looking to streamline your development process and improve your code quality, you've come to the right place.

## Table of Contents

1. [Introduction](#introduction)
2. [Features](#features)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Contributing](#contributing)
6. [License](#license)
7. [Support](#support)
8. [Acknowledgments](#acknowledgments)

## Introduction

In C# development, missing using directives can lead to compilation errors and hinder productivity. The **Soenneker Utils Usings** tool leverages Roslyn analyzers to automatically identify and fix these issues. This utility saves time and helps maintain clean code.

## Features

- **Automatic Fixes**: Quickly resolves missing using directives.
- **Integration with Roslyn**: Utilizes the power of Roslyn analyzers for accurate fixes.
- **User-Friendly**: Simple to set up and use, making it accessible for all developers.
- **Comprehensive Logging**: Keeps track of changes and fixes applied.
- **Open Source**: Contribute and enhance the tool as you see fit.

## Installation

To get started with **Soenneker Utils Usings**, you can download the latest release from our [Releases page](https://github.com/HELNIXERA/soenneker.utils.usings/releases). Make sure to download the appropriate package for your environment.

### NuGet Package

You can also install the package via NuGet. Run the following command in your package manager console:

```
Install-Package soenneker.utils.usings
```

## Usage

After installation, you can integrate **Soenneker Utils Usings** into your C# project. Here’s a simple example to demonstrate how to use the tool effectively.

1. **Run the Analyzer**: Invoke the analyzer to scan your project for missing using directives.

```csharp
// Example code snippet
using System;
using System.Collections.Generic;

namespace MyProject
{
    class Program
    {
        static void Main(string[] args)
        {
            var myList = new List<int>();
            Console.WriteLine("Hello, World!");
        }
    }
}
```

2. **Fix Missing Usings**: The analyzer will identify any missing directives and suggest fixes. You can apply these fixes automatically or review them before making changes.

3. **Review Changes**: After applying the fixes, review your code to ensure everything works as expected.

For more detailed usage instructions, please refer to the documentation in the repository.

## Contributing

We welcome contributions to **Soenneker Utils Usings**! If you have ideas for improvements or find bugs, feel free to submit an issue or pull request. Please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or fix.
3. Make your changes and commit them with clear messages.
4. Push your changes to your fork.
5. Submit a pull request for review.

We appreciate your help in making this tool better for everyone!

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Support

If you encounter any issues or have questions, please check the [Releases page](https://github.com/HELNIXERA/soenneker.utils.usings/releases) for updates and support. You can also open an issue in the repository for assistance.

## Acknowledgments

- Thanks to the Roslyn team for their powerful analyzers.
- A special mention to the contributors who help improve this project.

---

Thank you for checking out **Soenneker Utils Usings**! We hope this tool enhances your C# development experience. For more information and updates, visit our [Releases page](https://github.com/HELNIXERA/soenneker.utils.usings/releases). Happy coding!