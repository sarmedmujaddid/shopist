# Project Name

Brief description of your project.

## Table of Contents

- [Technology Stack](#technology-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Technology Stack

- **Build Tool:** Visual Studio
- **Primary Language:** C#
- **UI Technology:** Selenium Webdriver
- **Test Framework:** NUnit Framework (PageObjectModel)

### NuGet Packages Used

- OpenQA.Selenium
- OpenQA.Selenium.Support.UI
- SeleniumExtras.PageObjects

## Installation

1. Clone the repository.
2. Open the project in Visual Studio.
3. Restore NuGet packages if needed.

## Usage

Provide brief instructions on how to use your project. Include any necessary setup steps, configuration, or environment variables.

### Examples

#### Profile Page Update

```csharp
ProfilePage profilePage = new ProfilePage(getDriver());
profilePage.updateProfile("Prenzlauer Promenade 182", "Second Floor, Left side", "Berlin", "AL", "13189");


