# mateus-amaral--common-snippets

download for vscode: https://marketplace.visualstudio.com/items?itemName=MateusAmaral.mateus-amaral--common-snippets

Common snippets for a better development experience

Examples for React Component:

in your component file type this command: "rfc"

```
export function Sidebar(){
return (
<div>
 <h1>Sidebar</h1>
</div>
);
}
```

in your file unit test file type this command: "rut"

```
import { render, screen } from '@testing-library/react';

describe('<Sidebar/>', () => {
it('deve renderizar componente', () => {
//Arrange
render(<Sidebar/>);

//Act

//Assert

expect(screen).toBeDefined();
});
});
```
