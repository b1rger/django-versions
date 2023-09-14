Django versions
===============

Provides an endpoint that lists versions of installed packages. The endpoint is
only activated if `DEBUG` is set to `true`.

# Usage

Add the package to your installed apps:
```Python
INSTALLED_APPS.append('django_versions')
```

Add the shipped ulrpatterns to your urlpatterns:
```Python
from django_versions.urls import urlpatterns as dvurlpatterns
urlpatterns = dvurlpatterns + urlpatterns
```
