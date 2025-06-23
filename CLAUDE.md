# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a simple static website for Butler Financial and Records PLLC, a freelance bookkeeping and data entry service. The site showcases Aimee Butler's professional services, education, and work experience.

## Architecture

- **Static HTML/CSS Website**: Single-page site with no build process
- **Files**:
  - `index.html`: Main HTML document containing service information and resume
  - `main.css`: Minimal CSS styling (currently only sets font-family)

## Development

Since this is a basic static website with no package.json or build tools:

- **No build process required** - files can be edited directly
- **No linting tools configured** - standard HTML/CSS validation applies
- **No test framework** - manual testing by opening `index.html` in browser
- **Local development**: Open `index.html` directly in a web browser

## Code Structure

The HTML follows a semantic structure:
- Header with business description
- Services section listing offerings
- Resume section with education and experience timelines
- Uses semantic HTML elements and CSS classes for styling

## Notes

- CSS is minimal with only basic font family declaration