# full_magphys_read
A slightly modified version of the Python module magphys_read_output (repository available at https://github.com/astronomeralex/magphys-read-output) to read also results coming from magphys+photoz.

Usage:
  import full_magphys_read
  z_type = 'spec' # or 'phot', if you know other ways to measure galaxy redshifts let me know
  results = full_magphys_read.MagphysOutput(path_to_fit, path_to_sed, z_type = z_type)
  
 Then all the magphys outputs will be stored in the results object.
