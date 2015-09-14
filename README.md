# soundtouch-ios-library
A soundtouch library compiled for iOS projects. Based on https://github.com/talko/soundtouch 

# Supported architectures
This library is compiled for *armv7*, *armv7s*, *arm64*, *i386* and *x86_64* architectures

You can check that with the following command:

`$> lipo -info SoundTouch/libSoundTouch.a `

And the output must be:

`Architectures in the fat file: SoundTouch/libSoundTouch.a are: armv7 armv7s arm64 i386 x86_64 `

# License

SoundTouch audio processing library Copyright (c) Olli Parviainen

This library is free software; you can redistribute it and/or modify it under the terms of the GNU Lesser General Public License version 2.1 as published by the Free Software Foundation.

This library is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU Lesser General Public License for more details.

You should have received a copy of the GNU Lesser General Public License along with this library; if not, write to the Free Software Foundation, Inc., 59 Temple Place, Suite 330, Boston, MA 02111-1307 USA
