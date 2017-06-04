<?php if ( ! defined('BASEPATH')) exit('No direct script access allowed');

class Garbage_model extends CI_Model {

	public $variable;

	public function __construct()
	{
		parent::__construct();
		
	}

	public function getOwner()
	{
		$this->db->select('uid, username, pass_word');
		$this->db->from('user_table');
		$query = $this->db->get();

		return $query->result();
	}

}

/* End of file garbage_model */
/* Location: ./application/models/garbage_model */
