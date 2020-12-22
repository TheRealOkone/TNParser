# TNParser
Библиотека для загрузки изображений, связанных с текстом, для Java.

Подключение 

    static {
        System.loadLibrary("TNParser");
    }
    static native void activate();
    static native void deactivate();

activate - запускает парсер, парсер невозможно отключить

deactivate - очищает папку с ресурсами парсера
