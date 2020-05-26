
Jinja2 template renderer

## Installation

### For Development

```
pip install -r requirements-devel.txt
python setup.py develop
```

### From Source

```
pip install -r requirements.txt
python setup.py install
```

### From PyPi

Install `yamja-renderer` on your system using:

```
pip install yamja-renderer
```

### Docker

```
docker build --no-cache --tag yamja-renderer .
docker run yamja-renderer --help
```

## Usage

Get basic usage info: `yamja-renderer --help`

### Examples

Execute with debug output:

`yamja-renderer --debug`

Sample usage:
`docker run --rm --user 1000:1000 --volume $PWD:/opt --workdir /opt yamja-renderer --variables configs --templates templates --output stacks`
