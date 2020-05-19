# element-el-popconfirm

#index.html 就是复现文件，点击弹出的气泡里的确认和取消都没有反应，我试过写@onConfirm ,浏览器会保错：

	vue.js:640 [Vue tip]: Event "oncancel" is emitted in component <ElPopconfirm> at packages/popconfirm/src/main.vue but the handler is registered for "onCancel". Note that HTML attributes are case-insensitive and you cannot use v-on to listen to camelCase events when using in-DOM templates. You should probably use "on-cancel" instead of "onCancel".