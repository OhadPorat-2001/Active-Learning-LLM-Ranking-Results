# Results of the article: Active Learning of Approximate LLM Ranking for Energy-Efficient Retrieval of Long Queries

This repository contains the document scores produced by LAAM, the lightweight model trained by active learning, on TREC topics 301–350.

## Files

| File | Contents |
|---|---|
| `laam_scores_k50_combined.csv` | LAAM scores after K=50 LLM-labeled documents |
| `laam_scores_k100_combined.csv` | LAAM scores after K=100 LLM-labeled documents |

Columns:

| Column | Description |
|---|---|
| `topic` | TREC topic number (301–350) |
| `field` | Topic field used as the query: `title`, `description` or `narrative` |
| `doc_id` | TREC document identifier |
| `laam_score` | Score assigned by LAAM. Documents are listed in ranked order within each topic and field |