<a name="readme-top"></a>

[![Contributors][contributors-shield]](https://github.com/gelndjj/Pword/graphs/contributors)
[![Forks][forks-shield]](https://github.com/gelndjj/Pword/forks)
[![Stargazers][stars-shield]](https://github.com/gelndjj/Pword/stargazers)
[![Issues][issues-shield]](https://github.com/gelndjj/Pword/issues)
[![MIT License][license-shield]](https://github.com/gelndjj/Pword/blob/main/LICENSE)
[![LinkedIn][linkedin-shield]](https://www.linkedin.com/in/jonathanduthil/)


<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/gelndjj/"Pword">
    <img src="https://github.com/gelndjj/Pword/blob/main/resources/image.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Pword</h3>

  <p align="center">
    Generate encrypted password and share with secure.
    <br />
    <a href="https://github.com/gelndjj/Pword"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    ·
    <a href="https://github.com/gelndjj/Pword/issues">Report Bug</a>
    ·
    <a href="https://github.com/gelndjj/Pword/issues">Request Feature</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>

  </ol>
</details>


<!-- ABOUT THE PROJECT -->
## About The Project
<div align="center">
<img src="https://github.com/gelndjj/Pword/blob/main/resources/main_windows.png" alt="Logo" width="541" height="393">
</br>
</br>
Having spare time ahead of me, I wanted to know what sharing online a password could look like.
Is there a way to make it hard to find out, without making one of 30 chars length ?</br>
</br>
Encryption was the way to go so I wrote this script that generate passwords, encrypt them and share by mail while giving to end user the tool to decrypt.
</div>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Built With

<a href="https://www.python.org">
<img src="https://github.com/gelndjj/Pword/blob/main/resources/py_icon.png" alt="Icon" width="32" height="32">
</a>
&nbsp;
<a href="https://customtkinter.tomschimansky.com">
<img src="https://github.com/gelndjj/Pword/blob/main/resources/ctk_icon.png" alt="Icon" width="32" height="32">
</a>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- USAGE EXAMPLES -->
## Usage
</br>

####  GENERATE AND ENCRYPT
##### By default, a 12 characters length password is generated, you can generate another length by changing the value or write your own password.
###### Once the password is generated click on **Encrypt**, Pword then creates three files.
- One is a text file containing the encrypted password.
- The second one is the *.key that is a crucial file to decrypt the encrypted password.
- The last one is a zip file containing both files previously quoted. The two files (.key and .txt) will be available in the combobox fields (as well as inside the directory where the script is launched) above the Decrypt button.

![Screenshot](https://github.com/gelndjj/Pword/blob/main/resources/files.png)

#### DECRYPT
##### When you encrypted a password, the generated .key and .txt files are named by the timestamp.Select the same .key and .txt then click on **Decrypt**.The password will be shown in the first field.
#### The password is automatically copied to the clipboard by clicking anywhere in the text field.

![Screenshot](https://github.com/gelndjj/Pword/blob/main/resources/decrypt_screenshot.png)

#### SEND ENCRYPTED PASSWORD BY EMAIL
###### Clicking on the **Send button** will open a filedialog where you can choose the zip file (that contains both key and text files), then the application MAIL (OSX) will be launched with the zip file attached to a new email. Write the mail of the person you want to send to and click on send.

![Screenshot](https://github.com/gelndjj/Pword/blob/main/resources/send_screenshot.png)



<!-- GETTING STARTED -->
## Standalone APP

Install pyintaller
```
pip install pyinstaller
```
Generate the standalone app
```
pyinstaller --onefile your_script_name.py
```


<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".


1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the GNU GENERAL PUBLIC LICENSE. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact


[LinkedIn](https://www.linkedin.com/in/jonathanduthil/)

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
[product-screenshot]: images/screenshot.png
[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[Vue-url]: https://vuejs.org/
[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
[Svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[Svelte-url]: https://svelte.dev/
[Laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[Laravel-url]: https://laravel.com
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com 
