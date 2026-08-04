# Rust eBooks Nightly

[![GitHub Pages Build Status](https://github.com/eetoeg/rust-ebooks/actions/workflows/publish.yml/badge.svg)](https://github.com/eetoeg/rust-ebooks/actions/workflows/publish.yml)

This project automatically builds and publishes the latest versions of top Rust books as eBooks – in EPUB, AZW3, MOBI and PDF formats.

Built fresh from source. Updated daily. Ready for offline reading.

Enjoy Rust books on your favorite device!

## Access the Books

Download the latest eBooks:  
[https://eetoeg.github.io/rust-ebooks](https://eetoeg.github.io/rust-ebooks/)

Browse the source code:  
[https://github.com/eetoeg/rust-ebooks](https://github.com/eetoeg/rust-ebooks)

## How It Works

Every day, a [GitHub Actions workflow](https://github.com/eetoeg/rust-ebooks/actions/workflows/publish.yml):

- Clones each book’s repository
- Builds the content with `mdBook`
- Converts it to eBook and PDF formats using Calibre
- Publishes the results to [GitHub Pages](https://eetoeg.github.io/rust-ebooks/)

If a book fails to build, it's skipped and a GitHub issue is created automatically. Other books continue building as usual.

## Author

Hi, I'm NOT Artur! Feel free to connect with him on [LinkedIn](https://www.linkedin.com/in/artursulej/) if you'd like to chat him about Rust, open source or anything tech-related! (credits to him)
