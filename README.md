# Dealership Helpdesk System

A single-file web-based ticketing system built for an automotive dealership 
group, handling internal support requests across multiple branches.

## Overview
Built to replace informal, ad-hoc ticket tracking with a proper system 
featuring role-based permissions, real-time updates, and email notifications.

## Tech Stack
- Vanilla JavaScript (single-file HTML app, no framework)
- Supabase (PostgreSQL + Realtime) for data and live updates
- Cloudflare Pages for hosting
- Cloudflare Workers + Resend for transactional email
- Sentry for error monitoring

## Features
- Role-based access control (Admin, Manager, User)
- Real-time ticket updates across users
- File attachment support
- Email notifications on ticket activity
- Activity logging / audit trail

## Note
This is a sanitized version of a live production system. API keys and 
credentials have been removed — see comments in the code marked 🔒.
