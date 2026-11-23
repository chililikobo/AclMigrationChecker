# Third-Party Software Notices and Information

ACL Migration Checker (`win-x64` NativeAOT Release distribution) incorporates components from the open-source projects listed below. Note that `AvaloniaUI.DiagnosticsSupport` is referenced only in `Debug` builds and is excluded from `Release` / published distributions.

Complete verbatim upstream third-party notices are also bundled as `ThirdPartyNotices.txt` in the Windows release package.

---

## 1. Avalonia UI (`12.1.6`)

* **Included Packages**: `Avalonia`, `Avalonia.Desktop`, `Avalonia.Themes.Fluent`, `Avalonia.Fonts.Inter`, `Avalonia.Win32`, `Avalonia.Skia`, `Avalonia.HarfBuzz`, `Avalonia.FreeDesktop`, `Avalonia.Native`, `Avalonia.X11`, `Avalonia.FreeDesktop.AtSpi`, `Avalonia.Remote.Protocol`, `Avalonia.BuildServices`
* **Project URL**: [https://avaloniaui.net/](https://avaloniaui.net/)
* **Repository**: [https://github.com/AvaloniaUI/Avalonia](https://github.com/AvaloniaUI/Avalonia)
* **License**: MIT License

```text
Copyright 2013-2026 © The AvaloniaUI Project

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of
the Software, and to permit persons to whom the Software is furnished to do so,
subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
```

---

## 2. .NET Runtime & .NET NativeAOT (`10.0.15`)

* **Repository**: [https://github.com/dotnet/runtime](https://github.com/dotnet/runtime)
* **License**: MIT License

```text
The MIT License (MIT)

Copyright (c) .NET Foundation and Contributors

All rights reserved.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

## 3. Inter Font (bundled via `Avalonia.Fonts.Inter 12.1.6`)

* **Repository**: [https://github.com/rsms/inter](https://github.com/rsms/inter)
* **License**: SIL Open Font License, Version 1.1

```text
Copyright 2020 The Inter Project Authors (https://github.com/rsms/inter)

This Font Software is licensed under the SIL Open Font License, Version 1.1.
This license is copied below, and is also available with a FAQ at:
https://openfontlicense.org

-----------------------------------------------------------
SIL OPEN FONT LICENSE Version 1.1 - 26 February 2007
-----------------------------------------------------------

PREAMBLE
The goals of the Open Font License (OFL) are to stimulate worldwide
development of collaborative font projects, to support the font creation
efforts of academic and linguistic communities, and to provide a free and
open framework in which fonts may be shared and improved in partnership
with others.

The OFL allows the licensed fonts to be used, studied, modified and
redistributed freely as long as they are not sold by themselves. The
fonts, including any derivative works, can be bundled, embedded, redistributed
and/or sold with any software provided that any reserved names are not
used by derivative works. The fonts and derivatives, however, cannot be
released under any other type of license. The requirement for fonts to remain
under this license does not apply to any document created using the fonts or
their derivatives.

DEFINITIONS
"Font Software" refers to the set of files released by the Copyright
Holder(s) under this license and clearly marked as such. This may include
source files, build scripts and documentation.

"Reserved Font Name" refers to any names specified as such after the
copyright statement(s).

"Original Version" refers to the collection of Font Software components as
distributed by the Copyright Holder(s).

"Modified Version" refers to any derivative made by adding to, deleting, or
substituting -- in part or in whole -- any of the components of the
Original Version, by changing formats or by porting the Font Software to a
new environment.

"Author" refers to any designer, engineer, programmer, technical
writer or other person who contributed to the Font Software.

PERMISSION & CONDITIONS
Permission is hereby granted, free of charge, to any person obtaining
a copy of the Font Software, to use, study, copy, merge, publish,
distribute, and sell modified and unmodified copies of the Font
Software, subject to the following conditions:

1) Neither the Font Software nor any of its individual components,
in Original or Modified Versions, may be sold by themselves.

2) Original or Modified Versions of the Font Software may be bundled,
redistributed and/or sold with any software, provided that each copy
contains the above copyright notice and this license. These can be
included either as stand-alone text files, human-readable headers or
in the appropriate machine-readable metadata fields within text or
binary files as long as those fields can be easily viewed by the user.

3) No Modified Version of the Font Software may use the Reserved Font
Name(s) unless explicit written permission is granted by the corresponding
Copyright Holder. This restriction applies only to the primary font name as
registered with the U.S. Patent and Trademark Office.

4) The name(s) of the Copyright Holder(s) or the Author(s) of the Font
Software shall not be used to endorse or promote products derived from
the Font Software without specific written permission.

5) The Font Software, modified or unmodified, in part or in whole,
must be distributed using this license, and may not be distributed under
any other license. The requirement for fonts to remain under this
license does not apply to any document created using the fonts or their
derivatives.

TERMINATION
This license becomes null and void if any of the above conditions are
not met.

DISCLAIMER
THE FONT SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT
OF COPYRIGHT, PATENT, TRADEMARK, OR OTHER RIGHT. IN NO EVENT SHALL THE
COPYRIGHT HOLDER BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY,
INCLUDING ANY GENERAL, SPECIAL, INDIRECT, INCIDENTAL, OR CONSEQUENTIAL
DAMAGES, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
FROM, OUT OF THE USE OF THIS FONT SOFTWARE OR THE ORIGINATOR OR
OTHERWISE.
```

---

## 4. ANGLE (`Avalonia.Angle.Windows.Natives 2.1.27548.20260419` / `av_libglesv2.dll`)

* **License**: BSD 3-Clause License

```text
Copyright 2018 The ANGLE Project Authors.
All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions
are met:

    Redistributions of source code must retain the above copyright
    notice, this list of conditions and the following disclaimer.

    Redistributions in binary form must reproduce the above
    copyright notice, this list of conditions and the following
    disclaimer in the documentation and/or other materials provided
    with the distribution.

    Neither the name of TransGaming Inc., Google Inc., 3DLabs Inc.
    Ltd., nor the names of their contributors may be used to endorse
    or promote products derived from this software without specific
    prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS
"AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT
LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS
FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE
COPYRIGHT OWNER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT,
INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING,
BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES;
LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER
CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT
LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN
ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE
POSSIBILITY OF SUCH DAMAGE.
```

---

## 5. CommunityToolkit.Mvvm (`8.4.2`)

* **Repository**: [https://github.com/CommunityToolkit/dotnet](https://github.com/CommunityToolkit/dotnet)
* **License**: MIT License

```text
Copyright © .NET Foundation and Contributors

All rights reserved.

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of
the Software, and to permit persons to whom the Software is furnished to do so,
subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED *AS IS*, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NON-INFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

## 6. SkiaSharp (`3.119.4` / `libSkiaSharp.dll`) & HarfBuzzSharp (`8.3.1.3` / `libHarfBuzzSharp.dll`)

* **Repository**: [https://github.com/mono/SkiaSharp](https://github.com/mono/SkiaSharp)
* **License**: MIT License

```text
Copyright (c) 2015-2016 Xamarin, Inc.
Copyright (c) 2017-2018 Microsoft Corporation.

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of
the Software, and to permit persons to whom the Software is furnished to do so,
subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
```

> Upstream third-party libraries bundled inside `libSkiaSharp.dll` and `libHarfBuzzSharp.dll` (including ANGLE, HarfBuzz, Skia, FreeType, libpng, libjpeg-turbo, libwebp, zlib, expat, ICU, DNG SDK, gif, piex, sfntly, SPIR-V Tools, etc.) are reproduced verbatim in `ThirdPartyNotices.txt` bundled with the release package.

---

## 7. Additional Transitive Open-Source Components (MIT License)

The following transitive dependencies are also licensed under the MIT License:

| Component | Version | Copyright / Author | Repository |
| --- | --- | --- | --- |
| **MicroCom.Runtime** | `0.11.6` | Copyright 2021 © Nikita Tsukanov | [kekekeks/MicroCom](https://github.com/kekekeks/MicroCom) |
| **Microsoft.IO.RecyclableMemoryStream** | `3.0.1` | © Microsoft Corporation | [Microsoft/Microsoft.IO.RecyclableMemoryStream](https://github.com/Microsoft/Microsoft.IO.RecyclableMemoryStream) |
| **Microsoft.Extensions.DependencyInjection.Abstractions** | `8.0.0` | Copyright (c) .NET Foundation and Contributors | [dotnet/runtime](https://github.com/dotnet/runtime) |
| **Microsoft.Extensions.Logging.Abstractions** | `8.0.0` | Copyright (c) .NET Foundation and Contributors | [dotnet/runtime](https://github.com/dotnet/runtime) |
| **Tmds.DBus.Protocol** | `0.94.1` | Copyright Tom Deseyn | [tmds/Tmds.DBus](https://github.com/tmds/Tmds.DBus) |

*(Each of the components above uses the standard MIT License terms set forth in Section 2.)*
