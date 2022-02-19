# Parson

![License](https://img.shields.io/github/license/zS1L3NT/rs-parson?style=for-the-badge) ![Languages](https://img.shields.io/github/languages/count/zS1L3NT/rs-parson?style=for-the-badge) ![Top Language](https://img.shields.io/github/languages/top/zS1L3NT/rs-parson?style=for-the-badge) ![Commit Activity](https://img.shields.io/github/commit-activity/y/zS1L3NT/rs-parson?style=for-the-badge) ![Last commit](https://img.shields.io/github/last-commit/zS1L3NT/rs-parson?style=for-the-badge)

Parson is a Rust crate that parses a JSON string so that the JSON data can be used in a Rust script

## Motivation

My interest in Rust is growing rapidly due to my boredom of TypeScript and Web Development. Making a Parson in Rust can possibly teach me a lot more about Rust than I currently know. Learning how to make a parser will also teach me about the steps to make a Lexer and a Parser. This is a stepping stone to making my own JavaScript interpreter, my Rust dream project.

## Features

-   JSON Parsing into Rust types
    -   A JSON String parses into a Rust owned string
    -   A JSON Number parses into a Rust f64
    -   A JSON Boolean parses into a Rust bool
    -   A JSON Null is not parsable into Rust since there is no Null value

## Usage

As of now, the Rust crate isn't available yet.

## Credits

I also learnt how to make a basic Parson from [here](https://notes.eatonphil.com/writing-a-simple-parson.html). I understood and improvised the way the author wrote the Lexer and Parsers to make the Parson more bug free

## Built with

-   Rust
    -   [![indexmap](https://img.shields.io/badge/indexmap-%5E1.8.0-blue?style=flat-square)](https://docs.rs/indexmap/1.8.0)
