# TimeConverter
Convert date/time across time zones

## Usage

- Find current time (based on any timezone)

  ```py  
  timeConvert('America/Los_Angeles', 'now')
  ```
  
- Convert date/time based on a timezone

  ```py
  timeConvert('America/Los_Angeles', '05122021 15:30:00')
  ```
  
  ```py
  timeConvert('Asia/Shanghai', '05132021 06:30:00')
  ```

- Time zone list: [can be found here](https://gist.github.com/heyalexej/8bf688fd67d7199be4a1682b3eec7568).
