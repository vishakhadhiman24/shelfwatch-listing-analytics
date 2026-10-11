# ShelfWatch — Analysis Plan

## Objective
Explore how listing price, review activity, and minimum-night requirements relate to reported listing availability.

## Business Questions

### 1. Price and Availability
**Question:** How does reported availability vary across listing price ranges?

**Metrics:** Median listing price and average reported availability, grouped into price bands.

### 2. Review Activity and Availability
**Question:** Is review activity associated with reported availability?

**Metrics:** Review counts and average reported availability, grouped by review activity.

### 3. Minimum Nights and Availability
**Question:** How does the minimum-night requirement relate to reported availability?

**Metrics:** Minimum-night requirement and average reported availability, grouped into sensible ranges.

## Data Quality Rules
- Check for duplicate listing IDs.
- Inspect missing values in fields used for analysis.
- Review zero and extreme prices before choosing price bands.
- Document exclusions and assumptions.

## Interpretation
`availability_365` measures reported available days, not actual occupancy. Results describe associations and do not establish causation.

## Status
Planning complete. Analysis pending.
