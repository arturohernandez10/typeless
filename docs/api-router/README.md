# Internals

Typeless already provides library code that maintains the router state. If you use he starter app the `RouteResolver` will traverse the features directory for interface files and map all the routes from the rest of the modules. For example:

```typescript
export const routeConfig: RouteConfig = {
  type: 'route',
  auth: false,
  path: '/login',
  component: <LoginRoute />,
};
```

Because `routeConfig` is exported with type 'route'. It will match the path '/login' and revolve the component. This is just a placeholder for users to customize path mapping.


