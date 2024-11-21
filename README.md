# RN Assignment

This challenge is designed to evaluate your ability to work with large datasets, implement pagination, and handle reactive filtering while maintaining performance and usability. The challenge mimics a real-world scenario that requires a mix of technical and design decisions.

*Do not spend more 2 hours on this test.*

## The Challenge

You are tasked with building a Product List Screen. The screen must display a large list of products, support infinite scrolling (pagination), and allow users to filter products by category using a simple dropdown or similar.

The dataset consists of 10,000 mock products spread across multiple categories. Your task is to:

- Implement pagination to load products in chunks as the user scrolls.
- Add a reactive filter dropdown to filter products by category.
- Optimize for performance to ensure smooth scrolling and quick rendering.

## Requirements

#### Pagination

- Display products in chunks of 20-50 items.
- Implement infinite scrolling to fetch more items when the user reaches the end of the list.
- Ensure there is no duplicate loading of items.

#### Reactive Filtering

- Add a dropdown at the top of the screen to filter products by category.
- Reset the pagination when a filter is applied.
- Use useEffect to handle the filtering and pagination logic reactively.

#### Performance Optimization

- Use React Native's FlatList with optimizations like keyExtractor, getItemLayout, and windowSize.
- Avoid rendering unnecessary items or causing jank during scrolling.

#### Error Handling

- Gracefully handle edge cases, such as:
- Empty states when no products match the filter.
- Errors while fetching the data (mock this with a timeout or random failure).

## Submission

- Push your solution to a public GitHub repository and share the link.
- Include a short README in your repository explaining:
  - How you implemented the features.
  - Any assumptions or trade-offs you made.
  - How you optimized performance.
- Ensure the app runs smoothly on both iOS and Android.
