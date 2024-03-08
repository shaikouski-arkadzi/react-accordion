## Compound Components
1. `useAccordionContext` - protection against attempts to use a children outside of parent(AccordionItem outside Accordion)
1. `Accordion.Item = AccordionItem;` - allows you to call the **AccordionItem** component via a call `<Accordion.Item >`

## Render Props
In the parent component
`{(item) => <Place item={item} />}`

In child component
`{children(item)}`

The component to which we pass the props
`Place({ item }) {}`
