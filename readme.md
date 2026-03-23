# Fake Users Generator

This directory contains scripts and data for generating fake user profiles for the e-commerce React application.

## Files

- `generateUsers.js` - Node.js script to generate 200 realistic user profiles
- `users.json` - Generated user data file containing detailed user information

## User Data Fields

Each generated user includes the following comprehensive information:

- **Basic Info**: name, email, age, gender, phone
- **Address**: street, city, state, zip code, country
- **Professional**: occupation, company, website
- **Personal**: bio, hobbies, skills
- **Social**: twitter, linkedin, github
- **System**: join date, last active, premium status
- **Preferences**: theme, language, notifications

## Usage

To generate new user data:

```bash
cd "fake users"
node generateUsers.js
```

This will:
1. Generate 200 unique user profiles
2. Save them to `users.json`
3. Display a success message with the file location

## Generated Data

The script creates realistic user data with:
- Random names from diverse backgrounds
- Valid email formats
- Realistic addresses
- Various occupations and companies
- Multiple hobbies per user
- Technical and soft skills
- Social media handles
- Random join dates within the last 5 years
- Mixed premium/free user statuses

## Integration

The generated `users.json` file can be used for:
- Testing authentication systems
- Populating user profiles
- Demo data for the e-commerce application
- Load testing user-related features
