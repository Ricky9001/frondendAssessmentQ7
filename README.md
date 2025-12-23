# Frontend Developer Assessment

Question 7: Debug & Refactor

(a) Issues occur:
1. Performance (API calls, filtering)
   - keep calling API on every filter change

2. Error handling
   - should use try-catch-finally

3. Typescript intergration
   - Type safety

4. State management
   - Same item may be added again without checking if only use .push() when add new item

5. Accessibility
   - Add alt attribute to image tag in case the image is not shown

6. CSS formatting
   - all using inline style


(b) Brief explanation of key improvements

The ProductList component requires several improvements to enhance performance and maintainability. In order to reduce unnecessary API calls due to filter change, use loadProducts() as the dependency instead of filter. For State management, directly use .push() with cart array may cause to insert duplicate item. Therefore, need to check whether the added item is already in the product list or not.

TypeScript integration will provide type safety that prevent errors during development. Error handling needs comprehensive implementation for API failures. Accessibility can be improved by adding alt texts for images in case of image cannot be shown.

CSS should be well formatting for more maintainable styling. These enhancements will significantly improve the component's performance, readability, and user experience.
