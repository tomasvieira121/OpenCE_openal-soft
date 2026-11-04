# openal-soft-headers

OpenAL Soft 1.25.2 public headers (`AL/al.h`, `AL/alc.h`, `AL/alext.h`,
`AL/efx.h`, `AL/efx-creative.h`, `AL/efx-presets.h`).

**Upstream**: https://github.com/kcat/openal-soft  
**Version**: 1.25.2  
**Commit**: release tag `1.25.2`  
**Licence**: MIT (see below)  
**Checksum** (openal-soft-1.25.2-bin.zip):
  downloaded by `tools/windows_build.py` from
  `https://github.com/kcat/openal-soft/releases/download/1.25.2/openal-soft-1.25.2-bin.zip`

**Used by**: `port/linux/src/dsound_openal.c` on Linux, Web and Android builds.
The Windows build uses the same version's headers from the binary zip that
`tools/windows_build.py` fetches into `build/windows/third_party/`.

The runtime library (`soft_oal.dll` / `libopenal.so`) is loaded dynamically
at run time, so these headers are only needed at compile time.

## Licence

```
OpenAL cross platform audio library
Copyright (C) 1999-2007 by authors.
www.openal.org

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:

* Redistributions of source code must retain the above copyright notice,
  this list of conditions and the following disclaimer.
* Redistributions in binary form must reproduce the above copyright notice,
  this list of conditions and the following disclaimer in the documentation
  and/or other materials provided with the distribution.
* Neither the name of the OpenAL team nor the names of its contributors may
  be used to endorse or promote products derived from this software without
  specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS"
AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE
ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT OWNER OR CONTRIBUTORS BE
LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR
CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF
SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS
INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN
CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE)
ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE
POSSIBILITY OF SUCH DAMAGE.
```

