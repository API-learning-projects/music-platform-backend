# Music platform backend

This repository contains code of a learning project called: "Music platform".

It's purpose is to build a REST API that allows users to find songs/creators.

## Learning

- Spring Boot
- Spring Data Meilisearch
- Spring Security
- Spring testing
- Meilisearch
- Weaviate
- Redis
- Caching
- Rate limiting
- UML diagrams
- Patterns
- SOLID
- GRASP

## Requirements

- A user must be logged in to do anything besides logging in.
- A user must be able to log in to their account and receive a JWT to identify themselves.
- A user must be able to quickly search for songs by giving a string input.
- A user must be able to quickly search for songs by giving a creator name.
- A user must be able to search for a creator based on a picture.
- A user must be able to search for songs that seem closest to the current song.
- A user must be able to see to play a song (Just a database record is enough).
- A user must be able to quickly see all their recently played songs (cached).
