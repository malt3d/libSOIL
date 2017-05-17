malt.soil
===

This is the soil library we use from malt engine

Currently, the only extension we have to the original SOIL is:

```
int malt_SOIL_test_memory(const unsigned char* const buffer, int len);
```

Which simply allows us to test whether a memory region can be loaded by soil or not before attempting to load it