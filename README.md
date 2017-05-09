# ppintrojunit5

## 1. Getting Started with JUnit 5
### 4 JUnit Platform
Launcher API
```
import org.junit.platform.launcher.TestExecutionListener;
import org.junit.platform.launcher.listeners.SummaryGeneratingListener;

TestExecutionListener listener = new SummaryGeneratingListener();
launcher.registerTestExecutionListener(listener);
launcher.execute(request);
```
