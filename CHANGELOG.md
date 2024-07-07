# Home Assistant Resources Changelog

# v0.1.2

- Ensure that tasks without due dates or times are always sorted to the end of the list
    - Before, there could be tasks without due dates or times spread throughout the list, since it only detected the relative order of tasks with due dates or times

# v0.1.1

- Sort tasks with due dates but without due times, after tasks with due dates that have due times (assume specific times are more important and should go first)

# v0.1.0

- Initial release of [blueprints/scripts/sort_todo.yaml](./blueprints/scripts/sort_todo.yaml)
