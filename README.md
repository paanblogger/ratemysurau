<!-- PROJECT SHIELDS -->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]

# Carisurau.com (Formerly Ratemysurau.com)

## About The Project

🔹 Lost in the mall? Can't find a surau nearby? Prayer time almost over? 🥲

🌐 Introducing [Carisurau.com](https://carisurau.com), the best solution to find surau wherever you are!

🕌 Discover nearby suraus and prayer rooms, ensuring you don't miss prayer time, even if you're in an unfamiliar place.

⭐️ Can't find the surau you want? You can make a difference by adding it to our platform! With just one click of the 'Add Surau' button, you can help others find their way to a place of prayer.

### Built With

- Next.js
- TRPC
- AWS Lambda dan S3
- PostgreSQL

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

Join us today and be part of this open source project that aims to make prayer accessible to all, everywhere.

### Pre-requisites

- NodeJS 18 (you can use [nvm](https://github.com/nvm-sh/nvm))
- [Docker](https://www.docker.com)
- make
- [yarn](https://yarnpkg.com)
  - run `corepack enable` (Node.js >= 16.10)
  - run `npm i -g corepack` (Node.js < 16.10)
- [Google Identity](https://developers.google.com/identity/oauth2/web/guides/get-google-api-clientid)
- [UploadThing](https://uploadthing.com/)

### Installation

```bash
$ git clone git@github.com:farhan-helmy/ratemysurau.git

# Copy & update .env base on pre-requisite above
$ cp .env.example .env

$ yarn

# DB Setup
$ yarn db:setup
$ yarn db:migrate
$ yarn db:seed

$ yarn dev
```

## Roadmap

- [ ] Add tests

See the [open issues](https://github.com/farhan-helmy/ratemysurau/issues) for a full list of proposed features (and known issues).

## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<!-- MARKDOWN LINKS & IMAGES -->
[contributors-shield]: https://img.shields.io/github/contributors/farhan-helmy/ratemysurau.svg?style=for-the-badge
[contributors-url]: https://github.com/farhan-helmy/ratemysurau/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/farhan-helmy/ratemysurau.svg?style=for-the-badge
[forks-url]: https://github.com/farhan-helmy/ratemysurau/network/members
[stars-shield]: https://img.shields.io/github/stars/farhan-helmy/ratemysurau.svg?style=for-the-badge
[stars-url]: https://github.com/farhan-helmy/ratemysurau/stargazers
[issues-shield]: https://img.shields.io/github/issues/farhan-helmy/ratemysurau.svg?style=for-the-badge
[issues-url]: https://github.com/farhan-helmy/ratemysurau/issues
