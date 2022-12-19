# vue-styleguidist `defineExpose` bug reproduction

Steps:

0. `cat src/components/TestComponent.vue`. Note that there are two emits.
1. `npm ci`
2. `npx vue-docgen-cli src/components/TestComponent.vue`
3. `cat docs/src/components/TestComponent.md`. Note that there is no public function

