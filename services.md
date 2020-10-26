```
$this->addService('config', ConfigProvider::class);
$this->addService('request', RequestContainer::class);
$this->addService('router', RouteContainer::class);
$this->addService('session', 'SessionProvider');
$this->addService('authenticate', 'Authenticate');
$this->addService('query', 'QueryFactory');
```
