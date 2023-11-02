## init repo
`npm install` 

## Sonar issue S2699 - Add at least one assertion to this test case
- open  `src/app/app.component.spec.ts`
- the 3 unit tests raising a Sonar issue S2699
- if you remove the third test and remove the line `import { spy } from 'sinon';`, the Sonar issue S2699 is not raised anymore