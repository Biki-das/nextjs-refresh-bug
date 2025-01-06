## installation instruction

```
yarn install
```

```
yarn start
```

## Reproducing the bug

### vist the component folder and open the Component.tsx file

1 .try editing the Component File
the initial render is of a normal Component

2.comment out the Normal component and uncomment the Memo wrapped component

3.it does not render instead if you check the console you would see an error

4.try commenting the Memo out and then check the ForwardRef, the same thing happens
