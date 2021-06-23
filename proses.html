<?php

$idd = $_GET['idd'];

class codew {
	public $api_url = 'https://v1.wstore.co.id/'; // API URL
	public $api_id = '4989'; // API ID
	public $api_key = 'f668cc-dc5217-8049eb-819e2d-f7e71e'; // API KEY
	
	


public function refill($id) {
			return json_decode($this->connect($this->api_url.'refill', array('api_id' => $this->api_id, 'api_key' => $this->api_key, 'id' => $id)));
	}


	public function status_refill($refill_id) {
		return json_decode($this->connect($this->api_url.'status_refill', array('api_id' => $this->api_id, 'api_key' => $this->api_key, 'id' => $refill_id)));
	}

	private function connect($end_point, $post) {
		$_post = Array();
		if (is_array($post)) {
			foreach ($post as $name => $value) {
				$_post[] = $name.'='.urlencode($value);
			}
		}
		$ch = curl_init($end_point);
		curl_setopt($ch, CURLOPT_RETURNTRANSFER, 1);
		curl_setopt($ch, CURLOPT_POST, 1);
		curl_setopt($ch, CURLOPT_HEADER, 0);
		curl_setopt($ch, CURLOPT_FOLLOWLOCATION, 1);
		if (is_array($post)) {
			curl_setopt($ch, CURLOPT_POSTFIELDS, join('&', $_post));
		}
		curl_setopt($ch, CURLOPT_USERAGENT, 'Mozilla/4.0 (compatible; MSIE 5.01; Windows NT 5.0)');
		$result = curl_exec($ch);
		if (curl_errno($ch) != 0 && empty($result)) {
			$result = false;
		}
		curl_close($ch);
		return $result;
	}
}

// contoh penggunaan

$api = new codew();


$refill = $api->refill($idd);

print_r($refill);


print_r('<br>');

?>

