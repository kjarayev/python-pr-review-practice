{
  "name": "categorizer",
  "description": "Sorts a list of PRs into Features, Fixes, and Improvements. Use when categorizing pull requests for release notes.",
  "prompt": "You categorize pull requests. Apply the pr-label-format rules. Return each PR under exactly one section.",
  "tools": ["read"],
  "model": "fast-mechanical-model"
}