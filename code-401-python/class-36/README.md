# Read 36 : Data Fetching

## Beginner’s Guide to SWR: Data Fetching in React

Common data fetching practices such as the Fetch API or Axios library works well in React. They can be used to send and fetch data easily.

But what about caching or data pagination? Or automatic revalidation or request deduplication? Fetch and Axios only can send or fetch data, then return its response, and that’s it.

In this article, let me introduce you SWR, an amazing React Hooks library that takes data fetching in React to the next level.

SWR stands for stale-while-revalidate, a HTTP cache invalidation strategy popularized by HTTP RFC 5861. It basically means that it performs data fetching in 3 steps:

1. Returns cached data first (stale)
2. Sends the fetch request (revalidate)
3. Returns the up-to-date data

SWR is created by Vercel and one of its advantages is that it is a fast and lightweight package. It is a layer built on top of Fetch API and therefore provides additional features on top of just data fetching. These features include caching, pagination, auto revalidation and more.

## Why use SWR?

1. Built-in Cache + Real-Time Experience.

When we use Fetch or Axios for data fetching in React, we usually need to show the user some loading message or spinner while data is being fetched. Using SWR’s strategy, the user sees the cached (stale) data first and requests are automatically being cached. Components will always be constantly updated with the most recent data, ensuring UI will always be fast and reactive.

2. Auto Revalidation

SWR ensures that the user sees the most up-to-date data. So even with multiple tabs or windows, the data is always fresh and in sync when the window/tab is refocused.

## References

https://blog.openreplay.com/beginner-s-guide-to-swr-data-fetching-in-react
