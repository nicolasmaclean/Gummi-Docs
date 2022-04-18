# Persistent Singleton

namespace: [Gummi.Pattern.Singletons](../../Patterns/Singletons/Singletons.md)\
Inherits: `MonoBehaviour`

## Summary

Base class for singletons that will persist across scenes.

## Fields

`public static T Instance`: The instance of `T` in the scene. It may also be null if there are no instances in the scene.

## Methods

`protected virtual void Awake()`: enforces Singleton pattern.

`protected virtual void OnDestroy()`: sets `T.Instance` to null.
