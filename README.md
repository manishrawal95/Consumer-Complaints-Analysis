# Consumer Complaints Analysis

Exploratory analysis of CFPB consumer complaint data to understand which financial products generate the most disputes and how companies resolve them.

## Questions I was asking

- Which product categories have the highest complaint volumes — and is it concentrated in a few companies or industry-wide?
- How long does it actually take companies to respond, and does speed correlate with resolution quality?
- What percentage of complaints get resolved in the consumer's favor?

## Key findings

- Complaint distribution is highly skewed — a small number of product categories (credit reporting, mortgages, debt collection) account for the majority of volume
- Response time varies significantly by company size; larger institutions respond faster but don't necessarily resolve better
- "Closed with explanation" is the most common resolution — which often means the complaint was acknowledged but not necessarily remedied

## Stack

Python — pandas, matplotlib, seaborn

## Files

```
Consumer-Complaints.ipynb          # Full analysis
Consumer_Complaints.csv            # Raw CFPB complaint data
ConsumerComplaints_DataDictionary.csv  # Column definitions
```
