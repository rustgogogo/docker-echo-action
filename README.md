# Echo docker action

此操作将 "Hello World" 或 "Hello" + 要问候的人员的姓名打印到日志。

## Inputs

### `echo-what`

**必填** 要问候的人员的姓名。 默认值为 `"World"`。

## Outputs

### `time`

我们问候您的时间。

## Example usage

使用：actions/docker-echo-action@master
及：
  echo-what: 'Tom'
