<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Acai Bowl Customizer</title>
    <link href="https://fonts.googleapis.com/css2?family=Darumadrop+One&display=swap" rel="stylesheet">
    <script src="https://www.google.com/recaptcha/api.js" async defer></script>
    <style>
        * { box-sizing: border-box; font-family: 'Darumadrop One', Arial, sans-serif; }
        body { margin: 0; padding: 0; background: transparent; }
        .container { max-width: 600px; margin: 0; background: white; border-radius: 15px; box-shadow: 0 4px 15px rgba(0,0,0,0.1); padding: 30px; }
        .title { font-size: 18px; font-weight: 700; color: #1f2937; margin-bottom: 25px; text-align: center; line-height: 1.3; }
        .section-title { font-size: 16px; font-weight: 600; color: #374151; margin-top: 20px; margin-bottom: 15px; }
        .form-group { margin-bottom: 15px; }
        .form-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 12px; margin-bottom: 15px; }
        label { font-size: 12px; font-weight: 600; color: #374151; margin-bottom: 6px; display: block; }
        input, select { width: 100%; padding: 10px 12px; border: 1px solid #d1d5db; border-radius: 8px; font-size: 13px; font-family: 'Darumadrop One', Arial, sans-serif; }
        input:focus, select:focus { outline: none; border-color: #10b981; box-shadow: 0 0 0 3px rgba(16, 185, 129, 0.1); }
        .items-list { margin-bottom: 15px; }
        .item-row { display: flex; gap: 8px; margin-bottom: 10px; align-items: center; }
