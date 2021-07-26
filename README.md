# Blog-em Ipsum

### A React App for the Udemy course "React Query: Server State Management for React"

## Installation

Run `npm install`

## Running the App

Run `npm start`. The app will be found at [http://localhost:3000]

## Server

This app uses the [JSON Placeholder](https://jsonplaceholder.typicode.com/) server.

### QUESTIONS

- useQuery => 3 time if request is files (by default retries) => but configurable!
  - isFetching;
  - isLoading;
  - stale => staleTime
    - staleTime => it's for re-fetching;
    - cacheTime => 5min by default;
    - isFetching;
- useMutation => no retries by default if is no fetched (post/delete/update)
  - iddLoading no isFetching
  - isError
  - isSuccess
