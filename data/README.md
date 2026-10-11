# Dataset Documentation

## Source
The project uses a publicly sourced Airbnb listings dataset covering US listings in 2023.

## Purpose
The dataset supports exploratory analysis of listing prices, reported availability, review activity, and minimum-night requirements.

## Data Handling
- The original source file is retained separately.
- Data-quality issues and exclusions will be documented.
- Analysis will use a working copy where necessary.
- The dataset will not be redistributed through this repository until its applicable usage and redistribution terms have been checked.

## Key Fields
| Field | Description |
|---|---|
| `price` | Listed nightly price |
| `availability_365` | Reported available days over the next 365 days |
| `number_of_reviews` | Total reviews recorded |
| `number_of_reviews_ltm` | Reviews in the last twelve months |
| `reviews_per_month` | Reported average monthly review activity |
| `minimum_nights` | Minimum nights required per booking |
| `room_type` | Type of accommodation |
| `city` | City associated with the listing |

## Known Limitation
Reported availability does not equal actual occupancy, and review activity is not a direct measure of bookings.
