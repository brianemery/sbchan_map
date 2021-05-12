# sbchan_map
Plot a map of the Santa Barbara Channel in MATLAB

## Installation

It should be fine to put all these in a directory that is on the MATLAB path.

## Usage

    % Make the map ...
    sbchan_map

    % ... or with no bathymetry
    sbchan_map('nobathy'

    % see help for other uses and details ...
    help sbchan_map

    % ... for example ...
    % ... Remove some site labels:
    fn = {'ptc','rfg','cop','ssd','sci'};
    for i = 1:numel(fn), delete(H.sites.text.(fn{i})), end
  
    % ... or some site markers
    for i = 1:numel(fn), delete(H.sites.(fn{i})), end


    % or use the shortcut
    sbc





