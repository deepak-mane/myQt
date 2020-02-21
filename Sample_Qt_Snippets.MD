# Sample Qt Snippets

```sh

    for(int i{0}; i<1000000; i++) {
        qDebug() << " counting in ui thread... ";
        qDebug() << " counting : " << i <<
                    " thread  : " << QThread::currentThread() << " id : " <<
                    QThread::currentThreadId();
    }

```
