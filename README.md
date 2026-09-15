# Topic Signal Monitor

Personal, non-commercial, read-only public discussion trend analysis tool.

## Purpose

This project analyzes aggregate changes in public discussion topics over time.

The goal is to identify emerging topics and unusual increases in discussion activity relative to historical baselines.

## Architecture

The application will run locally using:

- Python for API access, topic extraction, and signal processing
- SQL Server for aggregate historical statistics and anomaly analysis

## Reddit Data Processing

The application may use the Reddit Data API in a read-only manner to analyze public Reddit posts and comments.

Public content may be processed temporarily to calculate aggregate metrics such as:

- Topic frequency
- Unique participant counts
- Topic acceleration
- Historical anomaly scores

Raw post and comment text will not be maintained as a permanent archive.

Long-term storage will primarily contain aggregate topic-level statistics. For selected signals, Reddit object IDs and public URLs may be retained for manual review.

## Reddit Interaction

The application will not:

- Post or comment
- Vote
- Send messages
- Moderate communities
- Automate interactions with Reddit users
- Build individual user profiles
- Sell, republish, or redistribute Reddit data

## Status

Early prototype / development.
