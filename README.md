# daydream-for-gridster
a simple daydream for gridster.js. resizes all gridster widgets to 1x1 and shuffles them over the grid.

## Usage

    <script type="text/javascript" src="js/daydream.js"></script>

## Optional Meta-Tags

    <meta name="daydream_starttime" content="<starttime>">
    <meta name="daydream_slowdown" content="<slowdown>">
    <meta name="daydream_gridmaxx" content="<gridmaxx>">
    <meta name="daydream_gridmaxy" content="<gridmaxy>">

* starttime

    (re)start daydream after <starttime> ms.
    defaults to 60000 (1min) if not set

* slowdown

    slowdown daydream animations by <slowdown> ms.
    defaults to 1000 (1sec) if not set

* gridmaxx, gridmaxy

    maximum gridsize in x and y coordinates to use for the animation.
    if both options are set to 0, max gridsize is calculated by the
    grids maximum dimensions. this is the default
