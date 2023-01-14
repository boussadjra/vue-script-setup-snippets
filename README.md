# Vue `script setup` snippets




<img alt="logo" src="/img/logo.png" width="200" height="200"/>

In VSCode search for **`vue-script-setup-snippets`** extension and install it. or install directly from [VSCode Marketplace](https://marketplace.visualstudio.com/items?itemName=BoussadjraBrahim.vue-script-setup-snippets)

## Features

This extension adds snippets for [Vue 3 script setup](https://vuejs.org/api/composition-api-setup.html) syntax.


## Snippets

>Note: `$1`, `$2`, etc. are placeholders. Press `Tab` to jump between placeholders.

| Snippet | Purpose |
| ------- | ------- |
| `ss-file` | Vue 3 script setup file |
| `ss-file-ts` | Vue 3 script setup file with typescript |
|`ss-ref` | `const $1 = ref($2)` |
|`ss-ref-ts` | `const $1: Ref<$2> = ref($3)` |
|`ss-props` | `const $1 = defineProps<$2>()` |
|`ss-props-ts` | `const $1 = defineProps<$2>()` |
|`ss-emit` | `const $1 = defineEmit<$2>()` |
|`ss-emit-ts` | `const $1 = defineEmit<$2>()` |
|`ss-context` | `const $1 = defineContext<$2>()` |
|`ss-context-ts` | `const $1 = defineContext<$2>()` |
|`ss-computed` | `const $1 = computed(() => $2)` |
|`ss-computed-ts` | `const $1: Ref<$2> = computed(() => $3)` |
|`ss-watch` | `watch($1, ($2) => {   $3 })` |
|`ss-watch-getter` | `watch(()=>$1, ($2) => {   $3 })` |
|`ss-ronly` | `const $1 = readonly($2)` |
|`ss-ronly-ts` | `const $1: Readonly<Ref<$2>> = readonly($3)` |
|`ss-weffect` | `watchEffect(() => {   $1 })` |
|`ss-wpeffect` | `watchPostEffect(() => {   $1 })` |
|`ss-wseffect` | `watchSyncEffect(() => {   $1 })` |
|`ss-prvd` | `const $1 = provide($2, $3)` |
|`ss-prvd-ts` | `const $1: InjectionKey<$2> = provide($3, $4)` |
|`ss-inject` | `const $1 = inject($2, $3)` |
|`ss-inject-ts` | `const $1: Ref<$2> = inject($3, $4)` |
|`ss-mnt` | `onMounted(() => {   $1 })` |
|`ss-upd` | `onUpdated(() => {   $1 })` |
|`ss-umnt` | `onUnmounted(() => {   $1 })` |
|`ss-bmnt` | `onBeforeMount(() => {   $1 })` |
|`ss-bupd` | `onBeforeUpdate(() => {   $1 })` |
|`ss-bumnt` | `onBeforeUnmount(() => {   $1 })` |
|`ss-err` | `onErrorCaptured(() => {   $1 })` |
|`ss-rtrk` | `onRenderTracked(() => {   $1 })` |
|`ss-rtrg` | `onRenderTriggered(() => {   $1 })` |
|`ss-act` | `onActivated(() => {   $1 })` |
|`ss-dact` | `onDeactivated(() => {   $1 })` |
|`ss-spf` | `onServerPrefetch(() => {   $1 })` |
|`ss-isref` | `isRef($1)` |
|`ss-unref` | `unref($1)` |
|`ss-toref` | `toRef($1, $2)` |
|`ss-torefs` | `toRefs($1)` |
|`ss-isprx` | `isProxy($1)` |
|`ss-isrct` | `isReactive($1)` |
|`ss-isrdo` | `isReadonly($1)` |
|`ss-ssref` | `shallowRef($1)` |
|`ss-trref` | `triggerRef($1)` |
|`ss-csref` | `customRef(($1) => {   return {     get: () => $2,     set: ($3) => $4   } })` |
|`ss-ssrct` | `shallowReactive($1)` |
|`ss-ssrdo` | `shallowReadonly($1)` |
|`ss-toraw` | `toRaw($1)` |
|`ss-mkraw` | `markRaw($1)` |
|`ss-efscp` | `effectScope(($1) => {   $2 })` |
|`ss-curscp` | `getCurrentScope()` |
|`ss-ondscp` | `onScopeDispose(() => {   $1 })` |
