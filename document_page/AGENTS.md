# document_page

## Purpose

A simple wiki: pages with an HTML body in categories (a page of type `category`
groups its children), a history of every change (`document.page.history`) and a menu
per category on request. Depends on `document_knowledge` for the app and the groups.

## Notes for 20.0

- Migrated from 19.0 by the open OCA migration pull request; this fork carries it until
  upstream merges it. It needs the 20.0 migration of `document_knowledge` (separate
  pull request in this fork).
- `test-requirements.txt` pins `document_knowledge` to the upstream pull request; drop
  the pin once `document_knowledge` is on 20.0.
- The page body is not translatable; a page is written in one language.
