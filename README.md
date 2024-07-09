# Initial Nuxt3 Frame

this initial nuxt3 frame you just use pnpm download and input pnpm run dev,you can use it in fast.

we sollect some good features for initial nuxt3 frame. 

- unocss
- nuxt-icons
- nuxt-images
- pinia && pinia-plugin-persitedstate/nuxt
- husky && lint-staged
- prettier
- eslint
- ...and so on

## Initial Nuxt3 Frame some Problems

1. when you input pnpm run dev,you can see wran,like this

   ```
   The glob option "as" has been deprecated in favour of "query". Please update as: 'raw' to query: '?raw', import: 'default'.
   ```

   - this warning is nuxt-icons problems and official not give a good idea to how to solve it.But it don't influence when you development.You can development and build in normal.
   - If you have idea to solve this warn.You can tell me or pull this code and fix it.