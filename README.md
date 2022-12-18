# Curriculum Vitae <a href="https://tectonic-typesetting.github.io"><img src="https://img.shields.io/badge/TeX-Tectonic-blue?style=for-the-badge"/></a><a href="https://taskfile.dev"><img src="https://img.shields.io/badge/go-Task-blue?style=for-the-badge&logo=task"/></a>

## Description

Keep my CV up to date on S3.

## Dependencies

`brew install tectonic go-task/tap/go-task`

## Usage

* Create the PDF with `task compile`
* Upload to S3 with `task upload`
* Cleanup debris with `task clean`

## Improvements

* Github Action to upload to S3 on every master push
