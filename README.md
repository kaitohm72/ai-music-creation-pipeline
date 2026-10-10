AI Music Creation Pipeline

A personal multilingual AI-powered music creation automation project developed by an independent developer based in Japan.

Project Overview

This project aims to automate the creation and preparation of original songs in three languages:

* Chinese
* English
* Japanese

The system is designed to create approximately three songs per day for personal songwriting and music production.

Song language, genre, themes, vocal style, and arrangement preferences are configurable.

Planned Features

* Generate original song lyrics in Chinese, English, and Japanese.
* Create multiple lyric drafts and select the strongest version.
* Perform language-specific reviews of emotional expression, rhyme, natural phrasing, song structure, and singability.
* Refine lyrics through multiple AI-assisted iterations.
* Generate detailed music style prompts covering instruments, vocals, arrangement, tempo, and mood.
* Generate square cover artwork with accurate multilingual song titles and credits.
* Schedule unattended daily execution using Python and Google Cloud Run Jobs.
* Deliver lyrics, music prompts, cover artwork, and generation reports by email.
* Integrate with the official Suno API, subject to approval and availability.

Planned Suno API Integration

The intended integration will automatically submit song titles, lyrics, and music style prompts through an authorized official Suno API.

The expected volume is approximately three songs per day across Chinese, English, and Japanese.

Ideally, generated songs will appear in the developer’s existing Suno account library for listening and manual downloading.

Automated audio downloads and music distribution are outside the scope of this project.

No unofficial API, unauthorized scraping, or account-access workaround is intended.

Technology Stack

* Python
* AI language and image generation services
* Google Cloud Run Jobs
* Google Cloud Scheduler
* Google Cloud Secret Manager
* YAML configuration
* Official Suno API (pending approval)

Multilingual Configuration

The planned system will support configurable song languages and styles.

Example:

daily_song_count: 3
songs:
  - language: zh
    theme: nostalgia
    genre: classic_pop_ballad
  - language: en
    theme: love
    genre: acoustic_pop
  - language: ja
    theme: life_and_memories
    genre: j_pop

Project Status

Planning and development stage.

Official Suno API access has not yet been granted. Integration will be implemented only after access approval and confirmation of the official API documentation.

Usage

This is a personal creative automation project, not a public API service or a commercial API platform.

Security

API keys, account credentials, personal information, and unreleased creative materials will not be committed to this public repository.
