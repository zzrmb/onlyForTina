---
layout: default
title: Shell dirname
---

## dirname

Use *dirname $0* to get script path

Sometimes when you run a shell scipt, the current path is not the script path. So you can get it use this command.
For example:

echo "Current path is `pwd`"
scriptPath=`dirname $0`
echo "The script is located at: $scriptPath"
