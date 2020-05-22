# GeoCoordinate

A re-implementation of GeoCoordinate class for .Net standard.</br>
This class is not an exact clone of System.Device.Location but an extension of the functionality of the original.</br>
You can install package by calling `Install-Package ExtendedGeoCoordinate`

Project is not complete so expect updates (current version is 0.3).

Differences between this class and the Microsoft default class are

<ol>
  <li> Object is immutable. Once created, it can not be edited.</li>
  <li> Distance calculation can be done in three possible ways (using three different formulas)
    <ul><li>Haversine Formula</li>
    <li>Spherical law of Cosines</li>
    <li>Vicenty's formula</li></ul></li>
  </ol>
