# Semantic-ui-react Invalid JSX Test App

After cloning, run ```yarn``` or ```npm i``` to install depencies.

Type ```yarn start``` to start the app and you should get an error similar to the following:

```
ERROR in src/App.tsx:25:8
TS2604: JSX element type 'Form' does not have any construct or call signatures.
    23 |         </Menu.Item>
    24 |       </Menu>
  > 25 |       <Form>
       |        ^^^^
    26 |         <Form.Field>
    27 |           <Form.Input/>
    28 |         </Form.Field>
```