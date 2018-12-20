# preact-native
native(java, object-c) implement of preactjs(https://preactjs.com/)

# container driver
these dom apis need to be implemented in preact-native

### node
* normalizedNodeName 
* parentNode [YES]
* removeChild [YES]
* style [YES]
* innerHTML [YES]
* addEventListener
* removeEventListener
* removeAttribute
* removeAttributeNS
* setAttributeNS
* setAttribute [YES]
* nodeName
* replaceChild
* lastChild
* insertBefore [YES]
* appendChild [YES]

### document
* createTextNode
* createElementNS
* createElement [YES]

# async layout & measure
* [AsyncLayoutInflater](https://developer.android.com/reference/android/support/v4/view/AsyncLayoutInflater.html)
* [facebook litho](https://github.com/facebook/litho/blob/master/docs/_docs/asynchronous-layout.md)
