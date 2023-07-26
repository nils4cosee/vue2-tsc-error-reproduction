# Reproduction 

```bash
npm install

npm run test:types
#
# > vue-tsc-error-reproduction@0.0.0 test:types
# > vue-tsc
#
# src/App.vue:3:20 - error TS2339: Property 'min' does not exist on type 'Ref<{ min: number; max: number; }>'.
#
# 3     Range: {{range.min}} - {{range.max}}
#                      ~~~
# 
# src/App.vue:3:36 - error TS2339: Property 'max' does not exist on type 'Ref<{ min: number; max: number; }>'.
# 
# 3     Range: {{range.min}} - {{range.max}}
#                                      ~~~
# 
# 
# Found 2 errors in the same file, starting at: src/App.vue:3
# 
#
```