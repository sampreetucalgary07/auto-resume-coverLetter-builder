# AI resume -job profile matcher

## Overview

This project harnesses the power of Large Language Model (LLM) APIs to revolutionize job profile analysis and matching. Our tool streamlines the recruitment process and empowers job seekers with valuable insights.

## Key Features

- **Job Description Summarization**: Condenses lengthy job postings into concise, easy-to-digest summaries.
- **Match Score Generation**: Calculates compatibility scores between candidate profiles and job requirements.
- **Skill Gap Analysis**: Identifies missing skills in candidate profiles compared to job postings.

## How to use it

Clone AI-resume-profile-matcher

```bash
  git clone https://github.com/sampreetucalgary07/AI-resume-profile-matcher.git

```

Activate python environment (optional!)

```bash
# Add your environment activation command here, e.g.:
# source venv/bin/activate

```

Install requirementments

```bash
pip install -r requirements.txt

```

Update path : data/resum_info.json with your profile

```bash

```

Create api_keys.json and add your google studio key in the following format:

```bash
{
  "google_api_studio": [YOUR_GEMINI_API_KEY]
}

```

RUN LOCALLY:

```bash
streamlit run Homepage.py
```

You can also deploy the app using streamlit cloud.

## Extra

Make use of the job tracker feature to keep track of the jobs you've applied to. Track changes and save it periodically.

## Contact

For any questions or feedback, please open an issue in the GitHub repository or contact the maintainer at [sam.vaidya.analyst@gmail.com].

## Roadmap and Upcoming Features

### Planned Enhancements

- [ ] Add more LLM models. Currently supports Gemini family of models.
- [ ] Generate resume and cover letter.

### Future Vision

🚀 Our goal is to transform job searching from a manual process into an intelligent, data-driven experience.

### Community Input

We encourage feature suggestions:

- Open GitHub issues
- Submit pull requests
- Participate in discussions

### Development Status

- [x] Basic job profile matching
- [x] AI-powered skill gap analysis
- [ ] Advanced matching algorithms

**Last Updated**: January 2025
