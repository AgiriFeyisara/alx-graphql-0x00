# Character Queries (GraphQL)

This directory contains GraphQL queries written to fetch character
information from the Rick and Morty API using the `character(id: ID!)` field.

## Endpoint

https://rickandmortyapi.com/graphql

## Fields retrieved

- id
- name
- status
- species
- type
- gender

Each `.graphql` file contains a query for character IDs 1, 2, 3, and 4.
Each corresponding `*-output.json` file contains the actual response
returned from the API.
