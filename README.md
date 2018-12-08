# React Component Identity

A component that always renders it's children.

In very few occations this component can make your code look better.

## Install

```sh
npm install --save react-component-identity
```

## Usage

```tsx
import Identity from 'react-component-identity';
import MyComponent from './my_component';

// The following:

<MyComponent />

// Would result in the same html as

<Identity>
  <MyComponent />
</Identity>
```

## License

MIT © Fabio Spampinato
