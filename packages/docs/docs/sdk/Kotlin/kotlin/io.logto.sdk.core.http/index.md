# io.logto.sdk.core.http


## Types

| Name | Summary |
|---|---|
| [HttpCompletion](-http-completion/index.md) | fun interface [HttpCompletion](-http-completion/index.md)&lt;[T](-http-completion/index.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)&gt; |
| [HttpEmptyCompletion](-http-empty-completion/index.md) | fun interface [HttpEmptyCompletion](-http-empty-completion/index.md) |
| [HttpRawStringCompletion](index.md#1273102375%2FClasslikes%2F-470698881) | typealias [HttpRawStringCompletion](index.md#1273102375%2FClasslikes%2F-470698881) = [HttpCompletion](-http-completion/index.md)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt; |

## Functions

| Name | Summary |
|---|---|
| [httpGet](http-get.md) | inline fun &lt;[T](http-get.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)&gt; [httpGet](http-get.md)(uri: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), completion: [HttpCompletion](-http-completion/index.md)&lt;[T](http-get.md)&gt;)<br/>@[JvmName](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-name/index.html)(name = &quot;httpRawGet&quot;)<br/>fun [httpGet](http-get.md)(uri: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), completion: [HttpRawStringCompletion](index.md#1273102375%2FClasslikes%2F-470698881))<br/>fun [httpGet](http-get.md)(uri: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), completion: [HttpEmptyCompletion](-http-empty-completion/index.md))<br/>inline fun &lt;[T](http-get.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)&gt; [httpGet](http-get.md)(uri: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), headers: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt;?, completion: [HttpCompletion](-http-completion/index.md)&lt;[T](http-get.md)&gt;)<br/>@[JvmName](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-name/index.html)(name = &quot;httpRawGet&quot;)<br/>fun [httpGet](http-get.md)(uri: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), headers: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt;?, completion: [HttpRawStringCompletion](index.md#1273102375%2FClasslikes%2F-470698881)) |
| [httpPost](http-post.md) | inline fun &lt;[T](http-post.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)&gt; [httpPost](http-post.md)(uri: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), body: RequestBody, completion: [HttpCompletion](-http-completion/index.md)&lt;[T](http-post.md)&gt;)<br/>@[JvmName](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-name/index.html)(name = &quot;httpRawPost&quot;)<br/>fun [httpPost](http-post.md)(uri: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), body: RequestBody, completion: [HttpRawStringCompletion](index.md#1273102375%2FClasslikes%2F-470698881))<br/>fun [httpPost](http-post.md)(uri: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), body: RequestBody, completion: [HttpEmptyCompletion](-http-empty-completion/index.md))<br/>inline fun &lt;[T](http-post.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)&gt; [httpPost](http-post.md)(uri: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), body: RequestBody, headers: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt;?, completion: [HttpCompletion](-http-completion/index.md)&lt;[T](http-post.md)&gt;)<br/>@[JvmName](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-name/index.html)(name = &quot;httpRawPost&quot;)<br/>fun [httpPost](http-post.md)(uri: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), body: RequestBody, headers: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt;?, completion: [HttpRawStringCompletion](index.md#1273102375%2FClasslikes%2F-470698881)) |
| [makeRequest](make-request.md) | fun [makeRequest](make-request.md)(uri: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), body: RequestBody?, headers: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt;?, completion: [HttpRawStringCompletion](index.md#1273102375%2FClasslikes%2F-470698881))<br/>fun [makeRequest](make-request.md)(uri: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), body: RequestBody?, headers: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt;?, completion: [HttpEmptyCompletion](-http-empty-completion/index.md))<br/>fun [makeRequest](make-request.md)(uri: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), body: RequestBody?, headers: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt;?, responseCallback: Callback) |

## Properties

| Name | Summary |
|---|---|
| [gson](gson.md) | val [gson](gson.md): Gson |
| [httpClient](http-client.md) | val [httpClient](http-client.md): OkHttpClient |