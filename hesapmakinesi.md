
private void BtnTopla_Click(object sender, EventArgs e)
        {
            double sayi1 = Convert.ToDouble(txtSayi1.Text); //string ifadeyi double tipine çevirme
            double sayi2 = Convert.ToDouble(txtSayi2.Text);
 
            double sonuc = sayi1 + sayi2; 
 
            txtSonuc.Text = sonuc.ToString(); //double ifadeyi string olarak yazdırma
        }
 
        private void BtnCikar_Click(object sender, EventArgs e)
        {
            double sayi1 = Convert.ToDouble(txtSayi1.Text); //string ifadeyi double tipine çevirme
            double sayi2 = Convert.ToDouble(txtSayi2.Text);
 
            double sonuc = sayi1 - sayi2;
 
            txtSonuc.Text = sonuc.ToString();
        }
 
        private void BtnCarp_Click(object sender, EventArgs e)
        {
 
            double sayi1 = Convert.ToDouble(txtSayi1.Text); //string ifadeyi double tipine çevirme
            double sayi2 = Convert.ToDouble(txtSayi2.Text);
 
            double sonuc = sayi1 * sayi2;
 
            txtSonuc.Text = sonuc.ToString();
        }
 
        private void BtnBol_Click(object sender, EventArgs e)
        {
 
            double sayi1 = Convert.ToDouble(txtSayi1.Text); //string ifadeyi double tipine çevirme
            double sayi2 = Convert.ToDouble(txtSayi2.Text);
 
            if (sayi2 != 0)
            {
                double sonuc = sayi1 / sayi2;
                txtSonuc.Text = sonuc.ToString();
            }
 
            else
            {
                MessageBox.Show("Sıfıra bölüm tanımsızdır.");
            }
 
            
        }
