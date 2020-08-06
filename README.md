# About

This repository contains compiled texts (PDFs) for a bachelor thesis that I have written at Charles University in Prague, Faculty of Mathematics and Physics in 2019. The main goal of the thesis was to create an extensible application for creating texture atlases.

# Abstract

The goal of this thesis was to create an extensible application for packing
textures into texture atlases, that could then be used in 2D game development.
The extensibility lies in the possibility to create and import plugins, containing
algorithms for packing, image processing, and metadata exporting. The ability
to extend the application by means of plugins makes our application also suitable
for testing of newly invented algorithms or for testing of custom variations of the
existing ones.

The software solution includes application with user interface that allows the
user to create texture atlases and perform additional processing of the textures.
Apart from that, we have also included several default implementations of some
of the extensible components, namely: placement algorithms, image processing
tools and metadata exporters. The concrete algorithms that are implemented
in our solution are (among others): Bottom-left algorithm, Skyline algorithm,
Guillotine algorithm and also a genetic-based algorithm. All of that can be used
as a starting point when developing new plugins.

In addition to generating texture atlases, our application can also generate metadata,
that can then be imported by supported game frameworks or libraries. The
process of metadata serialization is also customizable, and so users can supply
the application with serializers that produce metadata that matches their needs.
Two metadata serializers are included in the application itself.

We have also performed several benchmarks regarding performance measured
in both time and area of the resulting texture atlas. The results of benchmarks
are included in the text.