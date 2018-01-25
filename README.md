# Change-Image
C#
private void TurnFacebutton_Click(object sender, EventArgs e)
        {
            //When amanpicturebox visible is false then show aman image whether ikaas image.
            if (!AMANpictureBox.Visible == true)
            {
                Aman();
            }
            else
            {
                ikaas();
            }
        }

        private void ikaas()
        {
            //when ikaas image will true  then display ikaas in turn face button.
            IKAASpictureBox.Visible = true;
            AMANpictureBox.Visible = false;
            TurnFacebutton.Text = "ikaas";
        }

        private void Aman()
        {
            //when aman image will true  then display aman in turn face button.
            IKAASpictureBox.Visible = false;
            AMANpictureBox.Visible = true;
            TurnFacebutton.Text = "aman";
        }
