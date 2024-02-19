## 使用方法

`Emit`デコレーターを使用して、Vue のイベントを発火するメソッドを定義できます。

`Emit`デコレーターは任意のイベント名をパラメーターとして受け取り、この名前が発火されるイベント名になります。そしてこのメソッドは値を返します。イベント名が省略された場合、メソッド名がデフォルトで使用されます。

[](./code-usage.ts ':include :type=code typescript')

## 非同期イベント

メソッドがプロミスを返した場合、プロミスのリゾルブ後にイベントは発火されます。

[](./code-asynchronous.ts ':include :type=code typescript')