# Vue Interview Questions

## 1. How can you instantly recognize whether a Vue SFC uses Options API or Composition API?

**Answer:**

- If the file uses `<script setup>`, it is Composition API.
- If the file has `export default { data(), methods, computed, watch, mounted... }`, it is Options API.
- If the file uses `setup()` inside `export default` or `defineComponent(...)`, it is Composition API (without `<script setup>`).
- If both styles appear together, it is a hybrid component.
