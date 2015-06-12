# CoreDataMultipleStoresObjC
Test code showing a simple problem using multiple stores in core data

This code has only a few lines modified from Apple's default CoreData template in Xcode for Objective-C. The difference is that rather than creating 1 persistent store, it creates 1000.

The key issue is that this application runs fine from within Xcode, but when run outside of Xcode, the application is unable to load all of the stores.
