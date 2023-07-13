# sample-vue-app

This sample vue app exhibits an issue with hashgraph/proto npm component.

To reproduce:

1) npm install
2) npm run dev
3) browse http://localhost:5173
4) browser console shows the following error message:

`HelloWorld.vue:20 Failed to decode key: TypeError: Cannot read properties of undefined (reading 'proto')
(anonymous) @ HelloWorld.vue:20
`