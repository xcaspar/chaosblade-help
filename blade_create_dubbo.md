# blade create dubbo

dubbo experiment

## Synopsis

Dubbo experiment for testing service delay and exception.

```text
blade create dubbo [flags]
```

## Examples

```text
dubbo delay --time 3000 --consumer --service com.example.service.HelloService
```

## Options

```text
  -h, --help   help for dubbo
```

## Options inherited from parent commands

```text
  -d, --debug   Set client to DEBUG mode
```

## SEE ALSO

* [blade create](blade_create.md)     - Create a chaos engineering experiment
* [blade create dubbo delay](blade_create_dubbo_delay.md)     - delay time
* [blade create dubbo threadpoolfull](blade_create_dubbo_threadpoolfull.md)     - Thread pool full
* [blade create dubbo throwCustomException](blade_create_dubbo_throwcustomexception.md)     - throw custom exception

### Auto generated by spf13/cobra on 11-Jul-2019

