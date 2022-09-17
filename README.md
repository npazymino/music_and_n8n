# Music and n8n
My n8n automations for sharing, organizing and enjoying music.

[![Apache 2.0 License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]


<h3 align="center">Music and N8N Automation Flows </h3>

  <p align="center">
    This set of N8N flows will let you share, organize and enjoy your music.
    <br />
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-project">About The Project</a></li>
    <li><a href="#built-with">Built With</a></li>
    <li><a href="#getting-started">Getting Started</a></li>
    <li><a href="#prerequisites">Prerequisites</a></li>
    <li><a href="#installation">Installation</a></li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

The project consists of a set of flows that will let you organize, share and enjoy your music. The flows were created in n8n, an open source automation tool.
<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With

* [![n8n][n8n]][n8n-url]
* [![JavaScript][JavaScript]][JavaScript-url]


<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

You'll need an n8n account, the desktop application installed or a cloud user account.

### Prerequisites

1. JavaScript basic knowledge
2. Algorithms basic knowledge
3. Control flow basic knowledge
4. Spotify API credentials
5. YouTube API credentials
6. Twitter API credentials


### Installation

1. Install n8n at [https://n8n.io](https://n8n.io/cloud?ref=nelsonpazymino&utm_source=affiliate)
2. Get a free API Key from Spotify [https://spotify.com](https://developer.spotify.com/documentation/web-api/)
3. Get a free API Key from YouTube [https://youtube.com](https://console.cloud.google.com/apis/dashboard)
4. Get a free API Key from Twitter [https://twitter.com](https://developer.twitter.com/en/docs/twitter-api/getting-started/getting-access-to-the-twitter-api)
5. Copy the JSON files and open then in n8n (desktop/cloud). 
6. Customize with own credentials and playlist URIs/IDs.     

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

Brief explanation of each flow:

**EmptyPlaylist.json**.- This flow will allow you to empty a Spotify playlist. Remove all the tracks and leave the playlist void. May take several executions if the playlist exceeds more than 256 tracks.

**PutTracksInSpotifyPlaylist.json**.- This flow will allow you to merge several playlists into a single Spotify playlist. The criteria must be edited as per needed.

**PromoteArtistOnTwitter.json**.- This flow will allow you to share a Twitter thread with an artist Spotify playlist link and subsequent top 10 songs, one per tweet including a YouTube video. The criteria must be edited as per needed.

**AlbumsFromSpotifyPlaylist.json**.- This flow will allow you to get all the albums represented within a Spotify playlist and store them in a Excel file. The criteria must be edited as per needed.

**ShareAlbumOfTheYearOnTwitterFromFile.json**.- This flow will allow you to share a list of albums in Twitter in a thread (Spotify link + popular YouTube videos). The list will be contained in an Excel file (sample file _albums2022.xlsx_ provided). The criteria must be edited as per needed.

Recommendation: Allow no more than 3 albums per day to avoid consuming all the YouTube API request limit.

**SeveralPlaylistsToFile.json**.- This flow will allow you to merge several playlists into a single Excel file in order to be exported. The criteria must be edited as per needed.

**DivideSpotifyPlaylistByReleaseYearV2.json**.- This flow will allow you to divide a playlist into several playlists. The criteria must be edited as per needed, right now the criteria is _release year_ of the song.




<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the Apache 2.0 License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Your Name - [@nelo_1980](https://twitter.com/nelo_1980) - npazymino@gmail.com

Project Link: [/npazymino/music_and_n8n](https://github.com/npazymino/npazymino/music_and_n8n)

<p align="right">(<a href="#readme-top">back to top</a>)</p>





<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/npazymino/music_and_n8n.svg?style=for-the-badge
[contributors-url]: https://github.com/npazymino/music_and_n8n/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/npazymino/music_and_n8n.svg?style=for-the-badge
[forks-url]: https://github.com/npazymino/music_and_n8n/network/members
[stars-shield]: https://img.shields.io/github/stars/npazymino/music_and_n8n.svg?style=for-the-badge
[stars-url]: https://github.com/npazymino/music_and_n8n/stargazers
[issues-shield]: https://img.shields.io/github/issues/npazymino/music_and_n8n.svg?style=for-the-badge
[issues-url]: https://github.com/npazymino/music_and_n8n/issues
[license-shield]: https://img.shields.io/github/license/npazymino/music_and_n8n.svg?style=for-the-badge
[license-url]: https://github.com/npazymino/music_and_n8n/blob/main/LICENSE
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/npazymino
[product-screenshot]: images/screenshot.png
[n8n.js]: https://img.shields.io/badge/n8n.js-000000?style=for-the-badge&logo=n8n&logoColor=white
[n8n-url]: https://n8n.io/
[JavaScript.js]: https://img.shields.io/badge/JavaScript-20232A?style=for-the-badge&logo=JavaScript&logoColor=61DAFB
[JavaScript-url]: https://https://openjsf.org/
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


