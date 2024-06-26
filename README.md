![LogExpress logo](./90_image/lx_logo.png)
> An equipment data acquisition system for Mettler Toledo balances, moisture analyzers, and pH meters, specially designed for grassroots users with limited IT skills and budget constraints. It is also the only shareware of its kind developed by an individual.
<!-- Live demo [_here_](https://www.example.com).--> 
## Contents
* [Why LogExpress?](#why-logexpress)
* [Features](#features)
* [Language](#language)
* [Technologies Used](#technologies-used)
* [License](#license)
* [Setup](#setup)
* [Project Status](#project-status)
* [Contact](#contact)
<!--* * [Room for Improvement](#room-for-improvement) -->
<!--* * [Acknowledgements](#acknowledgements) -->
<!--* [Usage](#usage) -->

## Why LogExpress?
More than 70% of Taiwan's GDP is generated by the semiconductor and electronics industry. In these fields where yield is the primary indicator, there isn't a strict regulatory requirement, but there is a high demand for automation and system integration. Surprisingly, most enterprises are not that 'high-tech' in their data recording methods. "Drop to Cursor" is considered an advanced method for small and medium-sized enterprises. However, the data collection solutions on the market are either too complex or too simple and lack flexibility. Users generally lack a steppingstone to drive the process of data management. I often spend a lot of time helping users handle basic connections and data acquisition works, but they are still not satisfied with the existing software or solutions.
<br><br>
As a tool software oriented by end-user daily needs and specially designed for small and medium-sized instrument owners, LogExpress simultaneously captures data from METTLER balances, pH meters and moisture analyzers with one interface on PC and stores it in the same database. It's useful functions and high scalability can help disadvantaged users who are uncertain about the direction of data management, lack budget or IT capabilities, play a guiding and supportive role. For mid-to-high-end enterprises, it can be used as a transition tool to stabilize them before introducing high-end system, especially for most companies who are still stay in the stage of hybrid system. 
<br><br>
Based on respecting users' choices and investment costs, LogExpress has established basic information for nearly 500 models, allowing for quick identification of models and a seamless transition to usage. Whether catering to entry-level products or high-end models, users can easily manage their devices and leverage the cost-effectiveness of METTLER instruments. This not only satisfies owners but also prevents resource waste and protects our environment.
<br><br>
LogExpress is developed according to decades of experiences and industry requirements, aiming to align with industry practices and regulatory requirements as much as possible. But after all, it is a shared software developed by individual in my spare time. If you have any ideas for debugging, improvement, feature expansion, or any other suggestions, please feel free to contact me at any time. I would greatly appreciate your valuable feedback.
<br><br>

## Features
The brief features are as follows. See the files in the [02_Features_Function] folder for details.
- Supporting METTLER TOLEDO balances, halogen moisture analyzers, pH meters and printers.
- Utilizing an Microsoft SQL Server Express database for secure data storage.
- Providing support for over 50 default languages and one customized language. Offering a unique bilingual feature for logs and interface.
- Handling up to 40 devices concurrently without type, model, or license restrictions.
- Automatically detecting and identifying over 450 device models. Including basic specifications and tolerance informations.
- Providing various features to accommodate daily work scenarios and requirements.
- Offering a unique printer sharing feature and flexible report formats, making it the ideal solution for hybrid scenarios (combining paper and electronic records).
- Featuring user account and permission management, as well as event tracking.
- Offering customized data exports with the ability to schedule automatic execution.
- Offering two types of monitoring panels, allowing for easy device status monitoring through images, values, or real-time camera video.
- Customizable to meet specific requirements.
<br><br>

## Language
- Driven by the ideal of public contribution and the hope to help more grassroots users, this system comes with a built-in 52 languages vocabulary database and special bilingual function to achieve better localization through a friendly interface. For detailed information, please refer to the documents in the [01_Language_语言] folder.
- Thanks to Google Translate, it brings people closer. However, because the initial versions of each language in the database come from machine translation, there must be errors or inappropriate problems. If you are willing to make corrections and improvements to anyone language, I would greatly appreciate your support.
<br><br>

## Technologies Used
- .NET Framework 4.8
- Microsoft SQL Server Express 2022
- METTLER TOLEDO Standard Interface Command Set (MT-SICS) / Telegram Protocol
<br><br>

## License
- LogExpress (LX) is available for use in a non-profit, shareware format and is distributed under the terms of the End User License Agreement(EULA).
- For the purpose of public welfare and to help more METTLER users, LX is free to request a registration code, which has 14 days of full functional use before the registration process is completed, and there is no functional restriction or expiration date after the registration is completed. I hope it can be of assistance to every METTLER instrument owner. 
- Please refer to the steps in the [Setup] section to obtain the registration code.
<br><br>

## Setup
The installation process of LogExpress is simple.
1. Apply for a registration code.
    +  Please send an [Email](mailto:service@logexpress.tw?subject=Apply%20for%20register%20code) to apply for a registration code. Please indicate the following information in the letter:
      > * Your country
      > * Your full name
      > * The software will be used by individual, or your organization (please indicate the name of the organization)
      > * The model and quantity of instruments you intend to connect.
      > * The main purpose of using this software.

    +  The above information will be kept confidential in compliance with the Personal Information Protection Act and will not be used for other commercial purposes. It is mainly used to statistically evaluate the suitability of software for users. And when you encounter technical problems, I can provide appropriate assistance based on correct information.
2. After receiving your email, I will provide you with the registration code and download point.
3. Please refer to the installation guide file in the [00_Start_Start] folder to complete the installation and registration, which typically takes only 5 to 10 minutes.
<br><br>

## Project Status
- Released for testing on 2023/04/12.
- Officially announced on 2023/12/15.
<br><br>

## Contact
Please communicate on the discussion board or feel free to contact me directly in Chinese/English.<br>
[LogExpress Website](https://www.logexpress.tw/) <br>
[@Chris Hu](mailto:service@logexpress.tw) <br><br>
May the Force be with you.

<!-- Optional -->
<!-- ## Room for Improvement -->
<!-- Include areas you believe need improvement / could be improved. Also add TODOs for future development. -->
<!-- ## Acknowledgements -->
<!-- Give credit here. -->
<!-- - This project was inspired by... -->
<!-- - This project was based on [this tutorial](https://www.example.com). -->
<!-- - Many thanks to... -->
<!-- ## Usage -->
<!-- How does one go about using it? -->
<!-- Provide various use cases and code examples here. -->
<!-- To do: -->
<!-- - Feature to be added 1 -->
<!-- - Feature to be added 2 -->
<!-- write-your-code-here -->
