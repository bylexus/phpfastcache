### phpFastCache V5 Roadmap

- [x] Refactoring driver to be psr6 compliant
- [x] Rewrite examples by drivers
- [x] Rewrite examples for complex setups 
- [x] Rewrite examples for non-composer users
- [x] Re-implement standalone Autoload for non-composer user
- [x] Rewrite examples for ssdb lib
- [x] Rewrite Readme 
- [ ] Rewrite Wiki 
- [ ] Rewrite tests
- [x] Rewrite stats method to be implemented in a driverStatistic() object, not a breaking change due to ArrayAccess use, but array use is deprecated
- [ ] Re-implement searchByValue(), searchByTag() and searchByKey() methods in ExtendedCacheItemPoolInterface 
- [x] Re-implement [in|de]crement methods in ExtendedCacheItemInterface 
- [x] Re-implement touch method in ExtendedCacheItemInterface: deprecated in profit CacheItemInterface::expiresAfter()
- [ ] Implement MongoDb Driver
- [ ] Check Wincache driver in real Windows env (and not in VM)
- [ ] Final code review + psr2 checks + psr-6 null value as legitimates value.