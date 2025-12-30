# Gemini Context: FoodSmash

## Project Overview

**FoodSmash** is a Nuxt 3 web application designed to demonstrate the capabilities of the Gemini CLI. It serves as a "dummy" application for finding and sharing unique food combinations.

*   **Type:** Web Application
*   **Framework:** Nuxt 3 (Vue.js 3)
*   **Language:** TypeScript
*   **Styling:** Custom CSS (`app/assets/css/main.css`)
*   **Icons:** `lucide-vue-next`

## Architecture & Structure

The project follows a Nuxt 3 structure with the source code located in the `app/` directory.

*   `app/` - Main source directory.
    *   `app.vue` - Root component.
    *   `layouts/` - Layout components (e.g., `default.vue`).
    *   `pages/` - Application routes (e.g., `index.vue`, `create.vue`).
    *   `assets/css/` - Global styles.
*   `test/` - Test files (Vitest).
    *   `nuxt/` - Nuxt environment tests.
*   `nuxt.config.ts` - Main configuration file.
*   `vitest.config.ts` - Testing configuration.

## Building and Running

### Prerequisite
Ensure Node.js is installed.

### Commands

*   **Install Dependencies:**
    ```bash
    npm install
    ```

*   **Run Development Server:**
    ```bash
    npm run dev
    ```
    Access at `http://localhost:3000`

*   **Build for Production:**
    ```bash
    npm run build
    ```

*   **Run Tests:**
    ```bash
    npm run test
    ```

## Development Conventions

*   **Components:** Use Vue 3 `<script setup lang="ts">` syntax.
*   **Styling:** Use standard CSS classes defined in `app/assets/css/main.css` or scoped styles.
*   **Icons:** Import icons from `lucide-vue-next` (e.g., `import { BookOpen } from 'lucide-vue-next';`).
*   **Testing:** Write tests using Vitest. Unit/Integration tests are located in `test/`. Use `@nuxt/test-utils` for testing Nuxt-specific functionality.


### Additional Coding Preferences

* Do not use semicolons for any Javascript/Typescript.
* Do not use Tailwind classes in components templates.
* Keep project dependencies minimal.
* Use relative imports and NOT a path alias.
