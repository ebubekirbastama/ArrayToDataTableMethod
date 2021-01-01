using System.Data;

//EBS Time Her zaman Ayaktadır :)
namespace ebstimecms
{
    public class kategoriler
    {
        static DataTable dt;
        public static string[] katname = {
    "ALES Soru Bankası Kitapları",
    "ALES Yaprak Test Kitapları",
    "DGS  Kitapları",
    "DGS Deneme Sınavları Kitapları",
    "DGS Konu Anlatımlı Kitapları",
    "DGS Soru Bankası Kitapları",
    "DGS Yaprak Test Kitapları",
    "İlköğretim Yardımcı  Kitapları",
    "KPSS  Kitapları",
    "KPSS ÖABT Çıkmış Sorular Kitapları",
    "KPSS ÖABT Deneme Sınavları Kitapları"
};
        public static string[] katid = {
    "372",
    "551",
    "557",
    "446",
    "489",
    "440",
    "434",
    "535",
    "511",
    "439",
    "445",
    "418"
};
        public static DataTable ConvertToDatatble()
        {
            dt = new DataTable();
            dt.Columns.Add("İD");
            dt.Columns.Add("Kategori Ad");
            for (int i = 0; i < katname[i].Length; i++)
            {
                dt.Rows.Add(katid[i],katname[i]); 
            }
            return dt;
        }
    }
}
