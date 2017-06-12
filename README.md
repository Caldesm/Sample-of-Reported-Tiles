# Sample-of-Reported-Tiles
/*! START TRANSACTION */;
CREATE TABLE sample_of_reported_titles (
  onetsoc_code CHARACTER(10) NOT NULL,
  reported_job_title CHARACTER VARYING(150) NOT NULL,
  shown_in_my_next_move CHARACTER(1) NOT NULL,
  FOREIGN KEY (onetsoc_code) REFERENCES occupation_data(onetsoc_code));
/*! COMMIT */;
/*! START TRANSACTION */;
