# Vue `script setup` snippets




<img alt="logo" src="/img/logo.png" width="200" height="200"/>

In VSCode search for **`vue-script-setup-snippets`** and install it.

## Features

This extension adds snippets for [Vue 3 script setup](https://vuejs.org/api/composition-api-setup.html) syntax.


## Snippets

>Note: `$1`, `$2`, etc. are placeholders. Press `Tab` to jump between placeholders.

| Snippet | Purpose |
| ------- | ------- |
| `s-file` | Vue 3 script setup file |
| `s-file-ts` | Vue 3 script setup file with typescript |
|`s-ref` | `const $1 = ref($2)` |
|`s-ref-ts` | `const $1: Ref<$2> = ref($3)` |
|`s-props` | `const $1 = defineProps<$2>()` |
|`s-props-ts` | `const $1 = defineProps<$2>()` |
|`s-emit` | `const $1 = defineEmit<$2>()` |
|`s-emit-ts` | `const $1 = defineEmit<$2>()` |
|`s-context` | `const $1 = defineContext<$2>()` |
|`s-context-ts` | `const $1 = defineContext<$2>()` |
|`s-computed` | `const $1 = computed(() => $2)` |
|`s-computed-ts` | `const $1: Ref<$2> = computed(() => $3)` |
|`s-watch` | `watch($1, ($2) => {   $3 })` |
|`s-watch-getter` | `watch(()=>$1, ($2) => {   $3 })` |
|`s-ronly` | `const $1 = readonly($2)` |
|`s-ronly-ts` | `const $1: Readonly<Ref<$2>> = readonly($3)` |
|`s-weffect` | `watchEffect(() => {   $1 })` |
|`s-wpeffect` | `watchPostEffect(() => {   $1 })` |
|`s-wseffect` | `watchSyncEffect(() => {   $1 })` |
|`s-prvd` | `const $1 = provide($2, $3)` |
|`s-prvd-ts` | `const $1: InjectionKey<$2> = provide($3, $4)` |
|`s-inject` | `const $1 = inject($2, $3)` |
|`s-inject-ts` | `const $1: Ref<$2> = inject($3, $4)` |
|`s-mnt` | `onMounted(() => {   $1 })` |
|`s-upd` | `onUpdated(() => {   $1 })` |
|`s-umnt` | `onUnmounted(() => {   $1 })` |
|`s-bmnt` | `onBeforeMount(() => {   $1 })` |
|`s-bupd` | `onBeforeUpdate(() => {   $1 })` |
|`s-bumnt` | `onBeforeUnmount(() => {   $1 })` |
|`s-err` | `onErrorCaptured(() => {   $1 })` |
|`s-rtrk` | `onRenderTracked(() => {   $1 })` |
|`s-rtrg` | `onRenderTriggered(() => {   $1 })` |
|`s-act` | `onActivated(() => {   $1 })` |
|`s-dact` | `onDeactivated(() => {   $1 })` |
|`s-spf` | `onServerPrefetch(() => {   $1 })` |
|`s-isref` | `isRef($1)` |
|`s-unref` | `unref($1)` |
|`s-toref` | `toRef($1, $2)` |
|`s-torefs` | `toRefs($1)` |
|`s-isprx` | `isProxy($1)` |
|`s-isrct` | `isReactive($1)` |
|`s-isrdo` | `isReadonly($1)` |
|`s-ssref` | `shallowRef($1)` |
|`s-trref` | `triggerRef($1)` |
|`s-csref` | `customRef(($1) => {   return {     get: () => $2,     set: ($3) => $4   } })` |
|`s-ssrct` | `shallowReactive($1)` |
|`s-ssrdo` | `shallowReadonly($1)` |
|`s-toraw` | `toRaw($1)` |
|`s-mkraw` | `markRaw($1)` |
|`s-efscp` | `effectScope(($1) => {   $2 })` |
|`s-curscp` | `getCurrentScope()` |
|`s-ondscp` | `onScopeDispose(() => {   $1 })` |
