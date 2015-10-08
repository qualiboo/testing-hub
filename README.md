# Selenium Grid

This image provides a way to run Selenium Grid, based on the [official hub image](https://github.com/SeleniumHQ/docker-selenium).

## Usage

    docker run -d -p 4444:4444 --name selenium-hub qualiboo/testing-hub
    
Console will be accessible at [http://localhost:4444/grid/console](http://localhost:4444/grid/console)
    
## Author

Jean-François Lépine <www.qualiboo.com>

## License

See the LICENSE file.