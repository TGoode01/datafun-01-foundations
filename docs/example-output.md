# Example Output

> Output should look something like the following.

It should show information about the local machine without divulging any private info.

Code evolves so the following is a rough example and subject to change.

## Example App

After running:

```shell
uv self update
uv python install 3.14
uv sync --extra dev --extra docs --upgrade
uv run python src/datafun_01_foundations/app_case.py
```

```text
2026-01-11 17:00:59 | INFO | P01 | =================
2026-01-11 17:00:59 | INFO | P01 | === RUN START ===
2026-01-11 17:00:59 | INFO | P01 | project=Foundations of Professional Python
2026-01-11 17:00:59 | INFO | P01 | repo_dir=datafun-01-foundations
2026-01-11 17:00:59 | INFO | P01 | python=3.14.0
2026-01-11 17:00:59 | INFO | P01 | os=Windows 11
2026-01-11 17:00:59 | INFO | P01 | shell=powershell
2026-01-11 17:00:59 | INFO | P01 | cwd=.
2026-01-11 17:00:59 | INFO | P01 | github_actions=False
2026-01-11 17:00:59 | INFO | P01 | =================
2026-01-11 17:00:59 | INFO | P01 | START main()..................
2026-01-11 17:00:59 | INFO | P01 | Generated formatted multi-line SUMMARY string.
2026-01-11 17:00:59 | INFO | P01 | Returning the str to the calling function.
2026-01-11 17:00:59 | INFO | P01 |
    Course Information:
        Course name: Data Analytics Fundamentals
        Course number: 608
        Course hrs/wk: 20.00
        Assumes prior experience: False
        Uses Professional Python: True
        Helpful traits: ['patience', 'curiosity', 'humor', 'tenacity']

2026-01-11 17:00:59 | INFO | P01 | Generated formatted multi-line SUMMARY string.
2026-01-11 17:00:59 | INFO | P01 | Returning the str to the calling function.
2026-01-11 17:00:59 | INFO | P01 |
    Descriptive Statistics for Snowfall (inches):
        Total snowfall: 22.50 inches
        Count of measurements: 5
        Minimum snowfall: 2.50 inches
        Maximum snowfall: 6.50 inches
        Average snowfall: 4.50 inches
        Standard deviation: 1.58 inches

2026-01-11 17:00:59 | INFO | P01 | END main()..................
```

## Your App (Before Edits)

After running:

```shell
uv run python src/datafun_01_foundations/app_yourname.py
```

```text
2026-01-11 17:03:14 | INFO | P01 | =================
2026-01-11 17:03:14 | INFO | P01 | === RUN START ===
2026-01-11 17:03:14 | INFO | P01 | project=Foundations of Professional Python
2026-01-11 17:03:14 | INFO | P01 | repo_dir=datafun-01-foundations
2026-01-11 17:03:14 | INFO | P01 | python=3.14.0
2026-01-11 17:03:14 | INFO | P01 | os=Windows 11
2026-01-11 17:03:14 | INFO | P01 | shell=powershell
2026-01-11 17:03:14 | INFO | P01 | cwd=.
2026-01-11 17:03:14 | INFO | P01 | github_actions=False
2026-01-11 17:03:14 | INFO | P01 | =================
2026-01-11 17:03:14 | INFO | P01 | START main()..................
2026-01-11 17:03:14 | INFO | P01 | Generated formatted multi-line SUMMARY string.
2026-01-11 17:03:14 | INFO | P01 | Returning the str to the calling function.
2026-01-11 17:03:14 | INFO | P01 |
    Custom Information:
        Company name: DataFun Analytics
        Employee count: 150

        TODO: Add your other global variables below:
        COURSE_NAME: Final[str] = "Data Analytics Fundamentals"
COURSE_NUMBER: Final[int] = 608
COURSE_HOURS_PER_WEEK: Final[float] = 20.0
ASSUMES_PRIOR_EXPERIENCE: Final[bool] = False
USES_PROFESSIONAL_PYTHON: Final[bool] = True
HELPFUL_TRAITS: Final[list[str]] = [
    "patience",
    "curiosity",
    "humor",
    "tenacity",







2026-01-11 17:03:14 | INFO | P01 | Generated formatted multi-line SUMMARY string.
2026-01-11 17:03:14 | INFO | P01 | Returning the str to the calling function.
2026-01-11 17:03:14 | INFO | P01 |
    Descriptive Statistics for Snowfall (inches):
        Total snowfall: 22.50 inches
        TODO: Add your count of measurements below:
           snowfall_inches: list[float] = [2.5, 3.5, 4.5, 5.5, 6.5]

        TODO: Add your minimum and maximum snowfall below:
            minimum: float = min(snowfall_inches) if count > 0 else 0.0
    maximum: float = max(snowfall_inches) if count > 0 else 0.0

        Average snowfall: 4.50 inches
        TODO: Add your standard deviation below:
        Standard deviation: {std_dev:.2f} inches


2026-01-11 17:03:14 | INFO | P01 | END main()..................
```
