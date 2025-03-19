# Super Duper Study Guide

This project processes educational PDFs to create flashcards suitable for import into GoodNotes 6.

## Project Overview

The project extracts example questions and answers from educational PDFs, creates variations of those questions, and formats them as flashcards. The process includes:

1. Identifying topics and sections from each PDF
2. Extracting all example questions and answers
3. Creating variations of each question
4. Formatting the content as flashcards

## Project Structure

- `input_pdfs/`: Directory containing PDFs to be processed
- `checkpoints/`: Directory containing checkpoint files for each processing stage
- `processed_pdfs.txt`: List of PDFs that have been processed

## Workflow

The project processes PDFs one at a time, with checkpoints after key steps to allow for easy resumption if the process is interrupted.
