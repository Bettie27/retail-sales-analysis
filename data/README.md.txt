# Data availability

The dataset used in this analysis is not publicly shareable.

This project assumes a transactional retail sales dataset used for performance
analysis, diagnostics, and commercial insight generation.

The dataset represents standard point-of-sale level data commonly found in
retail environments. Raw data is not included in this repository.


# Dataset Metadata

## Time Coverage
Multiple calendar years (32 months), aggregated and analyzed at monthly, sub-group, store and weekday within the notebook.

## Fields

| Field name      | Type        | Description |
|----------------|------------|-------------|
| transaction_id | String     | Unique identifier for each transaction |
| year           | Integer    | Calendar year |
| month_period   | String     | Year–month period (YYYY-MM) |
| weekday        | String     | Day of week |
| location       | String     | Store or channel identifier |
| group          | String     | Primary product group |
| sub_group      | String     | Product sub-category |
| quantity       | Integer    | Number of units sold |
| sale_amount    | Float      | Total sales value per transaction |

## Assumptions
- Each transaction represents a completed sale
- Sales values are recorded in a single consistent currency
- Quantity reflects units sold, not line items
- Product grouping reflects internal commercial categorization

## Notes
- Dataset structure is representative of real commercial retail data
- Field names and types are generalized to avoid disclosure of sensitive
  or proprietary information

