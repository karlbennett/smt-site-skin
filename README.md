<!---
Copyright (C) 2015  Karl Bennett

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.
-->
smt-site-skin
=============

This is the [Maven site skin](http://maven.apache.org/plugins/maven-site-plugin/examples/creatingskins.html) that is 
used by all the `shiver.me.timbers` projects. It is extremley minimalistic.

### Usage:

```xml
<?xml version="1.0" encoding="UTF-8"?>
<project xmlns="http://maven.apache.org/DECORATION/1.3.0"
         xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
         xsi:schemaLocation="http://maven.apache.org/DECORATION/1.3.0
         http://maven.apache.org/xsd/decoration-1.3.0.xsd">

    <skin>
        <groupId>shiver.me.timbers</groupId>
        <artifactId>smt-site-skin</artifactId>
        <version>1.0-SNAPSHOT</version>
    </skin>

</project>
```
