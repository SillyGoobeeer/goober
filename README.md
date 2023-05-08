Add-Type -AssemblyName System.Windows.Forms
$form = New-Object -TypeName system.Windows.Forms.Form
$label = New-Object -TypeName System.Windows.Forms.Label
$label.Text = 'PowershellGuru'
$label.AutoSize = $true
$label.Location = New-Object -TypeName Drawing.Point -ArgumentList 5, 10
$button = New-Object -TypeName Windows.Forms.Button
$button.Text = 'OK'
$button.Location = New-Object -TypeName Drawing.Point -ArgumentList 5, 30
$form.Controls.Add($label)
$form.Controls.Add($button)
$form.ShowDialog()
