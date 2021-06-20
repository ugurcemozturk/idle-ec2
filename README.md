[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]


<!-- PROJECT LOGO -->
<br />
<p align="center">
  <h3 align="center">IDLE-EC2</h3>

  <p align="center">
    Monitor and notify your idle AWS EC2 resources. 
    <br />
    <br />
    <a href="https://github.com/ugurcemozturk/idle-ec2/issues">Report Bug</a>
    ·
    <a href="https://github.com/ugurcemozturk/idle-ec2/issues">Request Feature</a>
  </p>
</p>

<!-- ABOUT THE PROJECT -->
## About The Project

Even if there are many other ways to notify the EC2 underutiliztion like CloudWatch alarms and your custom webhook, however, 
you may need/want to configure it in your own way.

Here's why:

* This sample repository uses CPU metrics and send alert to a medium , i.e. a slack channel. However, you may need to configure as like:
** If CPU under ##, then notify team X. If network is over ##, then also notify team Y, and such.   
* You can automate your instance lifecyle and codify your EC2 management.
* You can generate a report with this tool and combine it with `AWS Trusted Advisor` to include or exclude resources from your advisor report. 

### Built With

No huge dependencies, or custom shit. Just fundamentals.
* [AWS GO SDK](github.com/aws/aws-sdk-go)

<!-- GETTING STARTED -->
## Getting Started

TODO

### Prerequisites

TODO

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/ugurcemozturk/idle-ec2.git
   ```
2. TODO, put what needs to be changed in configs and such.


## Usage

TODO: Tell how to use from locally or via a lambda or such. 

TODO: Add some troubleshooting steps.

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


## License
Distributed under the MIT License. See `LICENSE` for more information.

<!-- CONTACT -->
## Contact

Uğur Cem Öztürk - [Linkedin](https://www.linkedin.com/in/ugurcemozturk/) - ugurcem.dev@gmail.com

Project Link: [https://github.com/ugurcemozturk/idle-ec2](https://github.com/ugurcemozturk/idle-ec2)



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/ugurcemozturk/idle-ec2.svg?style=for-the-badge
[contributors-url]: https://github.com/ugurcemozturk/idle-ec2/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/ugurcemozturk/idle-ec2.svg?style=for-the-badge
[forks-url]: https://github.com/ugurcemozturk/idle-ec2/network/members
[stars-shield]: https://img.shields.io/github/stars/ugurcemozturk/idle-ec2.svg?style=for-the-badge
[stars-url]: https://github.com/ugurcemozturk/idle-ec2/stargazers
[issues-shield]: https://img.shields.io/github/issues/ugurcemozturk/idle-ec2.svg?style=for-the-badge
[issues-url]: https://github.com/ugurcemozturk/idle-ec2/issues
[license-shield]: https://img.shields.io/github/license/ugurcemozturk/idle-ec2.svg?style=for-the-badge
[license-url]: https://github.com/ugurcemozturk/idle-ec2/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
[product-screenshot]: images/screenshot.png