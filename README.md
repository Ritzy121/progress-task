# iprogress-task

This project demonstrates that where the IProgress object is created affects what thread the progress handler runs on. 
When the IProgress object is created on the UI thread, the handler runs on the UI thread. When IProgress is created
on the Task thread, the handler runs on the Task thread (and requires more code to get back to the UI thread).

For more information, refer to this article: (ARTICLE LOCATION TBD)
