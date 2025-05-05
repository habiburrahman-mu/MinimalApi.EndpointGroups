# 📦 MinimalApi.EndpointGroups ![Work in Progress](https://img.shields.io/badge/Project-Work_in_Progress-orange)

> A clean, convention-based Minimal API endpoint discovery & group registration utility for .NET
> 

---

## ✨ Overview

**MinimalApi.EndpointGroups** makes it simple to organize and group your Minimal API endpoints cleanly - without hardcoded strings, scattered `MapGroup` calls, or redundant module classes.

It uses:

- **marker interfaces** to group endpoints by feature
- a **RoutePrefix attribute** to define the route prefix for a group
- a single central **auto-registrar** that discovers, groups, and registers all endpoints at startup
