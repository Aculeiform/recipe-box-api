2026-11-07 – Anonymous GET /recipes returns all recipes, including is_public:false
2026-11-07 – Anonymous PUT /recipes/1 can change existing recipes (e.g., title changed to Shakshuka but hacked)
2026-11-07 – Anonymous DELETE /recipes/4 can delete existing recipes; recipe disappears from subsequent GET /recipes
2026-11-07 – Undocumented/hidden endpoints (security by obscurity) are still accessible if someone knows the method and path; obscurity is not protection.
