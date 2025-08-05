# YCharts onboarding app

This is a Django application for onboarding to YCharts.

## Requirements

- UV, to manage the project's dependencies. To install UV, run the following command:

  ```bash
  curl -LsSf https://astral.sh/uv/install.sh | sh
  ```

## Installation

1. Clone the repository
2. Install dependencies with `uv sync --frozen --all-groups`. This will also install python with the correct version.

Dependencies are separated into two groups:

- Production: dependencies necessary for running the application.
- Development: dependencies necessary for developing and testing the application.

## Run the application locally

To run the application locally, you must run the following command:

```bash
uv run python manage.py runserver
```

## Testing

To run the tests, you must run the following command:

```bash
uv run python manage.py test
```
